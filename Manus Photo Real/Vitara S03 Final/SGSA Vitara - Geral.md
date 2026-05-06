# SGSA Vitara - Referências de Imagens

## Geral
- Estou reformando um Suzuki Vitara 1993 1.6 JLX Metal e estou usando a IA para fazer um estudo de acessórios e cores para decidir o que usar no carro real
- Para isso vamos partir de um conjunto de imagens do carro original, na cor branco glossy sem nenhum acessório. 
- Vamos então definindo diferentes configurações, que vamos chamar de "Setups" com diferentes acessórios. 
- O desenho básico de cada acessórios ja está definido nas imagens das configurações existente e devem servir de base para eventuais futuras configurações. 
- Leia essas instruções e depois espere eu enviar os arquivos de referencia para os Setups S00, S01, S02, e S03
- Depois de ler as instruções, incorpore em seu contexto e Vá me pedindo as imagens para cada uma dos setups, indicando a lista de imagens esperadas.

## Lista de Acessórios
- Parachoque de ferro offroad dianteiro com D-Rings vermelhas e com faróis de neblina circulares (projetores Bi-Xenon) embutidos no parachoques dianteiro, e dois faros de milha redondos de 7 polegadas instalados acima do para choque
- Parachoques de ferro offrod traseira com duas lâmpadas de LED quadradas embutidas para iluminação em caso de necessidade, da área atras do carro
- Bull bar simples, conforme aparece nas imagens que providenciarei. 
- Placa de Registro no padrão atual brasileiro ("padrão Mercosul") com o texto BRASIL na faixa azul acima, e com o registro CEN-0A06
- Fenders de roda, as molduras em torno da caixa de rodas
- Revestimento das caixas de ar
- Rocksliders simples compostos de uma barra de ferro, na lateral do carro, no lugar em que normalmente se instalam rocksliders.
- Pneu estepe instalado no local original do carro (no caso na porta traseira) com o mesmo tipo de roda usado no restante do carro)
- Setup de pneus 01: conjunto de pneus BFGoodrich All Terrain, maior que o original com rodas na cor prata conforme as imagens fornecidas, as rodas originais do Suzuki Vitara e Samurai
- Setup de pneus 02: conjunto de pneus sem marcação, do tipo Mud Terrain, ou pneu mud, maiores que os ATR. As rodas sao do memo modelo mas com uma alteração: tem o offset negativo, de forma que deixam os pneus mais "para fora" do carro. Caso ainda tenha duvidas sobre como desenhar essas rodas, elas sao iguais as originais somente invertidas para que tenham o offset negativo, pergunte-me por referencias caso precise
- Rack de teto offroad com duffel bags e canisters de combustivel
- Painel de trim na parte baixa da lateral da porta e do carro, cobrindo a lataria do carro. 
- Os acessórios serão especificados em cada configuração


## Formato do nome dos arquivos
- As imagens existentes tem uma regra de nomenclaturo que segue os seguintes itens
	- Setup 01, 02...: s01 s02
	- Nome do Setup: offroad_ligth
	- Cor: c01, c002
	- Nome da Cor: Branco Glossy
	- Vista: v01 
	- Nome da Vista: frente
	- Alternativa: alt01

Formato: `s[setup]_[setup_name]_c[color]_[color_name]_v[view]_[view_name]_alt[alternative].png`

Exemplos:
- `s03_final_c02_bege_jizan_v01_frente_alt01.png`
- `s03_final_c02_bege_jizan_v03_esquerda.png` (sem alt, pois V03 não tem alternativas)
- `s03_final_c09_azul_brisk_v02_frente_esquerda_alt02.png`



- Abaixo estão tabelas desses itens 

### Setups
S00: Carro original
S01: Offroad Leve
S02: Offroad
S03: Final

### Cores
- As cores com C são cores que serão usadas na lataria do carro, as partes de metal que estao em branco no carro original. 
C01: Branco Brilhante | Glossy White | Sólida Brilhante | Branco puro, reflexivo |
C02: Suzuki Bege Jizan | Suzuki Bege Jizan | Sólida Brilhante | Bege quente, tom areia
C03: Suzuki Superior White | Branco Polar | Polar White | Sólida Brilhante | Branco cool, tom neutro
C04: FIAT Cinza Strato | FIAT Cinza Strato | Sólida Brilhante | Cinza cool, tom médio | 
C05: Audi Cinza Nardo | Audi Cinza Nardo | Sólida Brilhante | Cinza warm, tom sofisticado
C06: Toyota Bege Areia | Toyota Beige Sand | Sólida Brilhante | Areia/bege quente
C07: Toyota Bege Marfim | Toyota Bege Marfim | Sólida Brilhante | Marfim/creme claro
C08: Land Rover Verde Keswick | Land Rover Keswick Green | Sólida Brilhante | Verde floresta escuro
C09: Suzuki Azul Brisk | Suzuki Azul Brisk | **METALLIC** | Azul brilhante metalizado
C10: Jeep Cinza Sting | Jeep Sting Gray | Sólida Brilhante | Cinza escuro agressivo
C11: Land Rover Defender Verde Grasmere | Defender Grasmere Green | Sólida Brilhante | Verde terroso escuro
C12: Camel Trophy Amarelo | Camel Trophy Yellow | Sólida Brilhante | Amarelo vibrante

- As cores com A são cores que serão usadas nos acessórios presentes em cada setup
A01: Cor preto fosco offroad, tipicamente usada em para-choques de ferro offroad
A02: Cor Grafite, como referencia a cor dos plásticos no Suzuki Jimny Versão Desert do mercado brasilerio

Ao gerar imagens nessas cores, buscar referencias pelo nome para as cores e montadoras. Se estiver em duvidas sobre a cor exata, perguntar no prompt


### Vistas
V01: Frente | Vista Frontal flat | carro visto de frente
V02: Frente Esquerda | Vista 3/4 de frente lateral esquerda do carro lado do motorista
V03: Esquerda| Vista lateral esquerda flat lado do motorista
V04: Traseira Esquerda | Vista 3/4 traseira lateral esquerda do cardo lado do motorista
V05: Traseira | Vista traseira flat

### Alternativas
Aqui vamos tratar de ter diferentes cores para os componentes frontais do veiculo que sao:
	- Grade frontal (slats) 
	- Moldura da grade frontal
	- Moldura dos faróis
	- Moldura inferior da grade e dos farois que fica entre o parachoque dianteiro e as outras peças 
Alt00: Todas essas peças na cor do carro
Alt01: Todas as peças na cor do carro exceto a grade frontal (slats) que eh na cor dos acessórios, quando não mencionado, na cor A01
Alt02: Todas as peças na cor dos acessórios, quando não mencionado, na cor A01, exceto a moldura inferior que é da cor do carro


## Setup S00 (Original)
Sem nenhum acessório, ou alteração, carro original conforme as imagens
### V01 - Frente


- Descrição: Vista frontal plana
---

### V02 - Frente Esquerda

- Descrição: Vista 3/4 frente-esquerda, moldura em C01, slats em A01 (preto fosco)

---

### V03 - Esquerda

- Descrição: Vista lateral esquerda, corpo e acessórios em cores padrão

---

### V05 - Traseira


- Descrição: Vista traseira plana, corpo e acessórios em cores padrão

---
### Lista de imagens fornecidas
Aqui a lista de imagens para referencia para S03 na cor C01, V01 a V05 (V01 e V02 com Alt01 e Alt02).

s00_original_c01_branco_glossy_v01_frente.png
s00_original_c01_branco_glossy_v02_frente_esquerda.png
s00_original_c01_branco_glossy_v03_esquerda.png
s00_original_c01_branco_glossy_v05_traseira.png



## Setup S01 (Offroad Leve)
Acessórios, conforme as imagens de referencias fornecidas, e conforme características descritas acima nesse arquivo
- Parachoque frontal offroad 
- Parachoque traseiro offroad 
- Sem Bullbar
- Farois de neblina e de milha conforme descrito acima
- Sem Rockslider
- Sem paineis "Trim" nas portas, as portas são na cor do carro
- Com Revestimento da caixa de ar
- Com Fenders de rodas 

### V01 - Frente

**Alternativa 01:** Moldura frontal em cor do carro, slats em A01
- Referência: 's01_offroad_leve_c01_branco_glossy_v01_frente_alt01.png'
- Tem alternativas: Sim
- Descrição: Vista frontal plana, moldura na cor do carro, slats em A01 (preto fosco)

**Alternativa 02:** Moldura grille e slats em A01
- Referência: 's01_offroad_leve_c01_branco_glossy_v01_frente_alt02.png'
- Tem alternativas: Sim
- Descrição: Vista frontal plana, moldura e slats em A01 (preto fosco)

---

### V02 - Frente Esquerda

**Alternativa 01:** Moldura grille em cor do carro, slats em A01
- Referência: 's01_offroad_leve_c01_branco_glossy_v02_frente_esquerda.png'
- Tem alternativas: Sim
- Descrição: Vista 3/4 frente-esquerda, moldura em C01, slats em A01 (preto fosco)

**Alternativa 02:** Moldura grille e slats em A01
- Referência: 's01_offroad_leve_c01_branco_glossy_v02_frente_esquerda_alt02.png'
- Tem alternativas: Sim
- Descrição: Vista 3/4 frente-esquerda, moldura e slats em A01 (preto fosco)

---

### V03 - Esquerda

**Única versão** (sem alternativas)
- Referência: 's01_offroad_leve_c01_branco_glossy_v03_esquerda.png'
- Tem alternativas: Não
- Descrição: Vista lateral esquerda, corpo e acessórios em cores padrão

---

### V04 - Traseira Esquerda

**Única versão** (sem alternativas)
- Referência: 's01_offroad_leve_c01_branco_glossy_v04_traseira_esquerda.png'
- Tem alternativas: Não
- Descrição: Vista 3/4 traseira-esquerda, corpo e acessórios em cores padrão

---

### V05 - Traseira

**Única versão** (sem alternativas)
- Referência: 's01_offroad_leve_c01_branco_glossy_v05_traseira.png'
- Tem alternativas: Não
- Descrição: Vista traseira plana, corpo e acessórios em cores padrão

---
### Lista de imagens fornecidas
Aqui a lista de imagens para referencia para S03 na cor C01, V01 a V05 (V01 e V02 com Alt01 e Alt02).

s01_offroad_leve_c01_branco_glossy_v01_frente_alt01.png
s01_offroad_leve_c01_branco_glossy_v01_frente_alt02.png
s01_offroad_leve_c01_branco_glossy_v02_frente_esquerda_alt01.png
s01_offroad_leve_c01_branco_glossy_v02_frente_esquerda_alt02.png
s01_offroad_leve_c01_branco_glossy_v03_esquerda.png
s01_offroad_leve_c01_branco_glossy_v04_traseira_esquerda.png
s01_offroad_leve_c01_branco_glossy_v05_traseira.png



---


## Setup S02 (Offroad)
Acessórios, conforme as imagens de referencias fornecidas, e conforme características descritas acima nesse arquivo
- Parachoque frontal offroad 
- Parachoque traseiro offroad 
- Sem Bullbar
- Farois de neblina e de milha conforme descrito acima
- Sem Rockslider
- Sem paineis "Trim" nas portas, as portas são na cor do carro
- Com Revestimento da caixa de ar
- Com Fenders de rodas 

### V01 - Frente

**Alternativa 01:** Moldura frontal em cor do carro, slats em A01
- Referência: 's02_offroad_c01_branco_glossy_v01_frente_alt01.png'
- Tem alternativas: Sim
- Descrição: Vista frontal plana, moldura na cor do carro, slats em A01 (preto fosco)

**Alternativa 02:** Moldura grille e slats em A01
- Referência: 's02_offroad_c01_branco_glossy_v01_frente_alt02.png'
- Tem alternativas: Sim
- Descrição: Vista frontal plana, moldura e slats em A01 (preto fosco)

---

### V02 - Frente Esquerda

**Alternativa 01:** Moldura grille em cor do carro, slats em A01
- Referência: 's02_offroad_c01_branco_glossy_v02_frente_esquerda.webp'
- Tem alternativas: Sim
- Descrição: Vista 3/4 frente-esquerda, moldura em C01, slats em A01 (preto fosco)

**Alternativa 02:** Moldura grille e slats em A01
- Referência: 's02_offroad_c03_branco_glossy_v02_frente_esquerda_alt02.webp'
- Tem alternativas: Sim
- Descrição: Vista 3/4 frente-esquerda, moldura e slats em A01 (preto fosco)

---

### V03 - Esquerda

**Única versão** (sem alternativas)
- Referência: 's02_offroad_c01_branco_glossy_v03_esquerda.webp'
- Tem alternativas: Não
- Descrição: Vista lateral esquerda, corpo e acessórios em cores padrão

---

### V04 - Traseira Esquerda

**Única versão** (sem alternativas)
- Referência: 's02_offroad_c01_branco_glossy_v04_traseira_esquerda.webp'
- Tem alternativas: Não
- Descrição: Vista 3/4 traseira-esquerda, corpo e acessórios em cores padrão

---

### V05 - Traseira

**Única versão** (sem alternativas)
- Referência: 's02_offroad_c01_branco_glossy_v05_traseira.webp'
- Tem alternativas: Não
- Descrição: Vista traseira plana, corpo e acessórios em cores padrão

---
### Lista de imagens fornecidas
Aqui a lista de imagens para referencia para S03 na cor C01, V01 a V05 (V01 e V02 com Alt01 e Alt02).

s02_offroad_c01_branco_glossy_v01_frente_alt01.png
s02_offroad_c01_branco_glossy_v01_frente_alt02.png
s02_offroad_c01_branco_glossy_v02_frente_esquerda_alt01.png
s02_offroad_c01_branco_glossy_v02_frente_esquerda_alt02.png
s02_offroad_c01_branco_glossy_v03_esquerda.png
s02_offroad_c01_branco_glossy_v04_traseira_esquerda.png
s02_offroad_c01_branco_glossy_v05_traseira.png



---




## Setup S03 (Final)
Acessórios, conforme as imagens de referencias fornecidas, e conforme características descritas acima nesse arquivo
- Parachoque frontal offroad 
- Parachoque traseiro offroad 
- Bullbar
- Farois de neblina e de milha conforme descrito acima
- Rockslider
- Sem paineis "Trim" nas portas, as portas são na cor do carro
- Revestimento da caixa de ar
- Fenders de rodas 

### V01 - Frente

**Alternativa 01:** Moldura frontal em cor do carro, slats em A01
- Referência: 's03_final_c01_branco_glossy_v01_frente_alt01.webp'
- Tem alternativas: Sim
- Descrição: Vista frontal plana, moldura na cor do carro, slats em A01 (preto fosco)

**Alternativa 02:** Moldura grille e slats em A01
- Referência: 's03_final_c01_branco_glossy_v01_frente_alt02.webp'
- Tem alternativas: Sim
- Descrição: Vista frontal plana, moldura e slats em A01 (preto fosco)

---

### V02 - Frente Esquerda

**Alternativa 01:** Moldura grille em cor do carro, slats em A01
- Referência: 's03_final_c01_branco_glossy_v02_frente_esquerda.webp'
- Tem alternativas: Sim
- Descrição: Vista 3/4 frente-esquerda, moldura em C01, slats em A01 (preto fosco)

**Alternativa 02:** Moldura grille e slats em A01
- Referência: 's03_final_c03_branco_glossy_v02_frente_esquerda_alt02.webp'
- Tem alternativas: Sim
- Descrição: Vista 3/4 frente-esquerda, moldura e slats em A01 (preto fosco)

---

### V03 - Esquerda

**Única versão** (sem alternativas)
- Referência: 's03_final_c01_branco_glossy_v03_esquerda.webp'
- Tem alternativas: Não
- Descrição: Vista lateral esquerda, corpo e acessórios em cores padrão

---

### V04 - Traseira Esquerda

**Única versão** (sem alternativas)
- Referência: 's03_final_c01_branco_glossy_v04_traseira_esquerda.webp'
- Tem alternativas: Não
- Descrição: Vista 3/4 traseira-esquerda, corpo e acessórios em cores padrão

---

### V05 - Traseira

**Única versão** (sem alternativas)
- Referência: 's03_final_c01_branco_glossy_v05_traseira.webp'
- Tem alternativas: Não
- Descrição: Vista traseira plana, corpo e acessórios em cores padrão

---
### Lista de imagens fornecidas
Aqui a lista de imagens para referencia para S03, C01 a C05, V01 a V05 (V01 e V02 com Alt01 e Alt02).

s03_final_c01_branco_glossy_v01_frente_alt01.png
s03_final_c01_branco_glossy_v01_frente_alt02.png
s03_final_c01_branco_glossy_v02_frente_esquerda_alt01.png
s03_final_c01_branco_glossy_v02_frente_esquerda_alt02.png
s03_final_c01_branco_glossy_v03_esquerda.png
s03_final_c01_branco_glossy_v04_traseira_esquerda.png
s03_final_c01_branco_glossy_v05_traseira.png



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

