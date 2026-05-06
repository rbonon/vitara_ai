# SGSA Vitara - Referências de Imagens

## Setup S03 (Final Configuration)

### V01 - Frente Flat

**Alternativa 01:** Moldura grille em cor do carro, slats em A01
- Referência: `/home/ubuntu/upload/s03_final_c01_branco_glossy_v01_frente_alt01.webp`
- Tem alternativas: Sim
- Descrição: Vista frontal plana, moldura em C01, slats em A01 (preto fosco)

**Alternativa 02:** Moldura grille e slats em A01
- Referência: `/home/ubuntu/upload/s03_final_c01_branco_glossy_v01_frente_alt02.webp`
- Tem alternativas: Sim
- Descrição: Vista frontal plana, moldura e slats em A01 (preto fosco)

---

### V02 - Frente-Esquerda 3/4

**Alternativa 01:** Moldura grille em cor do carro, slats em A01
- Referência: `/home/ubuntu/upload/s03_final_c01_branco_glossy_v02_frente_esquerda.webp`
- Tem alternativas: Sim
- Descrição: Vista 3/4 frente-esquerda, moldura em C01, slats em A01 (preto fosco)

**Alternativa 02:** Moldura grille e slats em A01
- Referência: `/home/ubuntu/upload/c03_final_c03_branco_glossy_v02_frente_esquerda_alt02.webp`
- Tem alternativas: Sim
- Descrição: Vista 3/4 frente-esquerda, moldura e slats em A01 (preto fosco)

---

### V03 - Lado Esquerdo

**Única versão** (sem alternativas)
- Referência: `/home/ubuntu/upload/s03_final_c01_branco_glossy_v03_esquerda.webp`
- Tem alternativas: Não
- Descrição: Vista lateral esquerda, corpo e acessórios em cores padrão

---

### V04 - Traseira-Esquerda 3/4

**Única versão** (sem alternativas)
- Referência: `/home/ubuntu/upload/s03_final_c01_branco_glossy_v04_traseira_esquerda.webp`
- Tem alternativas: Não
- Descrição: Vista 3/4 traseira-esquerda, corpo e acessórios em cores padrão

---

### V05 - Traseira Flat

**Única versão** (sem alternativas)
- Referência: `/home/ubuntu/upload/s03_final_c01_branco_glossy_v05_traseira.webp`
- Tem alternativas: Não
- Descrição: Vista traseira plana, corpo e acessórios em cores padrão

---

### V06 - Top-Down (Driver Side)

**Única versão** (sem alternativas)
- Referência: `/home/ubuntu/upload/c03_final_c01_branco_glossy_v06_overhead_alt01.png`
- Tem alternativas: Não
- Descrição: Vista de cima do lado do motorista, moldura em C01, slats em A01 (preto fosco)

---

## Cores Disponíveis (C01-C12)

| Código | Nome | Acabamento | Acessórios |
|--------|------|-----------|-----------|
| C01 | Glossy White | Sólida Brilhante | A01 (Offroad Black - Fosco) |
| C02 | Suzuki Bege Jizan | Sólida Brilhante | A01 (Offroad Black - Fosco) |
| C03 | Polar White | Sólida Brilhante | A01 (Offroad Black - Fosco) |
| C04 | FIAT Cinza Strato | Sólida Brilhante | A01 (Offroad Black - Fosco) |
| C05 | Audi Cinza Nardo | Sólida Brilhante | A01 (Offroad Black - Fosco) |
| C06 | Toyota Beige Sand | Sólida Brilhante | A01 (Offroad Black - Fosco) |
| C07 | Toyota Bege Marfim | Sólida Brilhante | A01 (Offroad Black - Fosco) |
| C08 | Land Rover Keswick Green | Sólida Brilhante | A01 (Offroad Black - Fosco) |
| C09 | Suzuki Azul Brisk | **METALLIC** | A01 (Offroad Black - Fosco) |
| C10 | Jeep Sting Gray | Sólida Brilhante | A01 (Offroad Black - Fosco) |
| C11 | Defender Grasmere Green | Sólida Brilhante | A01 (Offroad Black - Fosco) |
| C12 | Camel Trophy Yellow | Sólida Brilhante | A01 (Offroad Black - Fosco) |

---

## Regras de Geração

1. **Sempre usar `generate_image_variation`** (nunca `generate_image`)
2. **Referência = SEMPRE a imagem C01 original** da mesma vista
3. **Nunca usar imagens derivadas** como referência (evita degradação)
4. **Prompt deve incluir:** "exact template", "no reinterpretation", "match reference exactly"
5. **Acabamentos:**
   - C01-C08, C10-C12: Sólida Brilhante (glossy solid)
   - C09: Metallic
   - A01, A02: Fosca (matte)

---

## Nomenclatura de Arquivos

Formato: `s[setup]_[setup_name]_c[color]_[color_name]_v[view]_[view_name]_alt[alternative].png`

Exemplos:
- `s03_final_c02_bege_jizan_v01_frente_alt01.png`
- `s03_final_c02_bege_jizan_v03_esquerda.png` (sem alt, pois V03 não tem alternativas)
- `s03_final_c09_azul_brisk_v02_frente_esquerda_alt02.png`

---

## Status de Geração

### S03 C01 (Referência Base)
- ✅ V01 Alt01
- ✅ V01 Alt02
- ✅ V02 (referência)
- ✅ V03
- ✅ V04
- ✅ V05
- ✅ V06 Alt01

### S03 C02 (Bege Jizan)
- ✅ V01 Alt01
- ✅ V01 Alt02
- ✅ V02 Alt01
- ✅ V02 Alt02
- ❌ V03 (ERRO - precisa regenerar)
- ❌ V04 (ERRO - precisa regenerar)
- ❌ V05 (ERRO - precisa regenerar)
- ⏳ V06 Alt01 (não gerado ainda)

### S03 C03-C12
- ⏳ Pendente

---
