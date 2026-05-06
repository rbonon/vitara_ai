# SGSA Vitara - Tabela de Cores S03

## Cores do Carro (C01-C12)

| Código | Nome Português | Nome Inglês | Acabamento | Descrição | Status |
|--------|-----------------|------------|-----------|-----------|--------|
| C01 | Branco Brilhante | Glossy White | Sólida Brilhante | Branco puro, reflexivo | ✅ Referência |
| C02 | Suzuki Bege Jizan | Suzuki Bege Jizan | Sólida Brilhante | Bege quente, tom areia | ✅ Completo |
| C03 | Branco Polar | Polar White | Sólida Brilhante | Branco cool, tom neutro | ✅ Completo |
| C04 | FIAT Cinza Strato | FIAT Cinza Strato | Sólida Brilhante | Cinza cool, tom médio | ⏳ Pendente |
| C05 | Audi Cinza Nardo | Audi Cinza Nardo | Sólida Brilhante | Cinza warm, tom sofisticado | ⏳ Pendente |
| C06 | Toyota Bege Areia | Toyota Beige Sand | Sólida Brilhante | Areia/bege quente | ⏳ Pendente |
| C07 | Toyota Bege Marfim | Toyota Bege Marfim | Sólida Brilhante | Marfim/creme claro | ⏳ Pendente |
| C08 | Land Rover Verde Keswick | Land Rover Keswick Green | Sólida Brilhante | Verde floresta escuro | ⏳ Pendente |
| C09 | Suzuki Azul Brisk | Suzuki Azul Brisk | **METALLIC** | Azul brilhante metalizado | ⏳ Pendente |
| C10 | Jeep Cinza Sting | Jeep Sting Gray | Sólida Brilhante | Cinza escuro agressivo | ⏳ Pendente |
| C11 | Defender Verde Grasmere | Defender Grasmere Green | Sólida Brilhante | Verde terroso escuro | ⏳ Pendente |
| C12 | Camel Trophy Amarelo | Camel Trophy Yellow | Sólida Brilhante | Amarelo vibrante | ⏳ Pendente |

---

## Cores de Acessórios (A01-A02)

| Código | Nome Português | Nome Inglês | Acabamento | Descrição | Aplicação |
|--------|-----------------|------------|-----------|-----------|-----------|
| A01 | Offroad Preto | Offroad Black | Fosca (Matte) | Preto profundo, sem brilho | Para-choque, snorkel, rock sliders, fenders, grille slats (Alt01/Alt02), moldura grille (Alt02), moldura farol (Alt02) |
| A02 | Jimny Cinza Deserto | Jimny Desert Gray | Fosca (Matte) | Cinza grafite, sem brilho | Alternativa para acessórios (não usado em S03 C01-C03) |

---

## Nomenclatura de Arquivo

**Formato padrão:**
```
s03_final_c[XX]_[nome_cor]_v[X]_[vista]_alt[XX].png
```

**Exemplos:**
- `s03_final_c01_branco_glossy_v01_frente_alt01.png` - S03, C01, V01, Alt01
- `s03_final_c02_bege_jizan_v02_frente_esquerda_alt02.png` - S03, C02, V02, Alt02
- `s03_final_c03_polar_white_v03_esquerda.png` - S03, C03, V03 (sem alt, pois V03 não tem alternativas)

---

## Vistas (V01-V06)

| Código | Nome | Alternativas | Arquivo de Referência |
|--------|------|-------------|----------------------|
| V01 | Frente Flat | Alt01, Alt02 | `s03_final_c01_branco_glossy_v01_frente_alt01.webp` |
| V02 | Frente-Esquerda 3/4 | Alt01, Alt02 | `s03_final_c01_branco_glossy_v02_frente_esquerda.webp` |
| V03 | Lado Esquerdo | Não | `s03_final_c01_branco_glossy_v03_esquerda.webp` |
| V04 | Traseira-Esquerda 3/4 | Não | `s03_final_c01_branco_glossy_v04_traseira_esquerda.webp` |
| V05 | Traseira Flat | Não | `s03_final_c01_branco_glossy_v05_traseira.webp` |
| V06 | Top-Down (Driver Side) | Não | `s03_final_c01_branco_glossy_v06_overhead_alt01.png` |

---

## Status de Geração

### Por Cor

| Cor | V01 Alt01 | V01 Alt02 | V02 Alt01 | V02 Alt02 | V03 | V04 | V05 | V06 | Total |
|-----|-----------|-----------|-----------|-----------|-----|-----|-----|-----|-------|
| C01 | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | 8/8 |
| C02 | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ⏳ | 7/8 |
| C03 | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ⏳ | 7/8 |
| C04 | ⏳ | ⏳ | ⏳ | ⏳ | ⏳ | ⏳ | ⏳ | ⏳ | 0/8 |
| C05 | ⏳ | ⏳ | ⏳ | ⏳ | ⏳ | ⏳ | ⏳ | ⏳ | 0/8 |
| C06 | ⏳ | ⏳ | ⏳ | ⏳ | ⏳ | ⏳ | ⏳ | ⏳ | 0/8 |
| C07 | ⏳ | ⏳ | ⏳ | ⏳ | ⏳ | ⏳ | ⏳ | ⏳ | 0/8 |
| C08 | ⏳ | ⏳ | ⏳ | ⏳ | ⏳ | ⏳ | ⏳ | ⏳ | 0/8 |
| C09 | ⏳ | ⏳ | ⏳ | ⏳ | ⏳ | ⏳ | ⏳ | ⏳ | 0/8 |
| C10 | ⏳ | ⏳ | ⏳ | ⏳ | ⏳ | ⏳ | ⏳ | ⏳ | 0/8 |
| C11 | ⏳ | ⏳ | ⏳ | ⏳ | ⏳ | ⏳ | ⏳ | ⏳ | 0/8 |
| C12 | ⏳ | ⏳ | ⏳ | ⏳ | ⏳ | ⏳ | ⏳ | ⏳ | 0/8 |
| **TOTAL** | **3/12** | **3/12** | **3/12** | **3/12** | **3/12** | **3/12** | **3/12** | **1/12** | **22/96** |

---

## Resumo

- **Total de cores:** 12 (C01-C12)
- **Total de vistas:** 6 (V01-V06)
- **Alternativas:** V01 e V02 têm 2 alternativas cada
- **Total de imagens possíveis:** 96 (12 cores × 8 vistas/alternativas)
- **Imagens geradas:** 22 (C01 ref + C02 completo + C03 completo)
- **Imagens pendentes:** 74 (C04-C12 completos + V06 para C02-C03)

---
