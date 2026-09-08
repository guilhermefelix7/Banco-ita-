Claro — abaixo está o conteúdo **100% em Markdown**, pronto para copiar e colar diretamente no `README.md` do GitHub:

````
# 🎨 Design System — Itaú

![Design System Preview](./Guilherme%20felix.png)

> Guia visual com definição de cores, tipografia, escala tipográfica e exemplos de contraste.

---

## 📌 Sobre o projeto

Este projeto apresenta um **Design System** criado para padronizar a identidade visual de interfaces digitais.

O sistema reúne os principais elementos visuais utilizados no projeto:

- 🎨 Paleta de cores
- 🔤 Tipografia
- 📏 Escala tipográfica
- ♿ Contraste
- ✅ Cores de sucesso
- 🚨 Cores de perigo

---

## 🎨 Paleta de cores

### 🟠 Cores primárias

| Nome | Hex | Aplicação |
|---|---|---|
| **Primário -1** | `#CC4E00` | Variação escura |
| **Primário** | `#FF6200` | Cor principal |
| **Primário +1** | `#FF8133` | Variação clara |

### 🔵 Cores secundárias

| Nome | Hex | Aplicação |
|---|---|---|
| **Secundário -1** | `#539AE9` | Variação clara |
| **Secundário** | `#267FE3` | Cor secundária |
| **Secundário +1** | `#1866BE` | Variação escura |

### ⚫ Cores escuras

| Nome | Hex | Aplicação |
|---|---|---|
| **Dark +1** | `#403B3B` | Variação clara |
| **Dark** | `#262323` | Cor principal |
| **Dark -1** | `#0B0A0A` | Variação escura |

### ⚪ Cores claras

| Nome | Hex | Aplicação |
|---|---|---|
| **Light -1** | `#FFFFFF` | Branco |
| **Light** | `#F2F5F7` | Fundo claro |
| **Light +1** | `#D3DDE4` | Variação escura |

### 🟢 Cores de sucesso

| Nome | Hex | Aplicação |
|---|---|---|
| **Success +1** | `#7BE085` | Variação clara |
| **Success** | `#52D65F` | Cor principal |
| **Success -1** | `#2FC63E` | Variação escura |

### 🔴 Cores de perigo

| Nome | Hex | Aplicação |
|---|---|---|
| **Danger -1** | `#9E1500` | Variação escura |
| **Danger** | `#D11C00` | Cor principal |
| **Danger +1** | `#FF2705` | Variação clara |

---

## 🔤 Tipografia

A família tipográfica utilizada no Design System é a **Poppins**.

### Pesos

| Peso | Exemplo |
|---|---|
| Regular | Poppins |
| Medium | **Poppins** |
| Bold | **Poppins** |

---

## 📏 Escala tipográfica

A escala de fontes foi definida para criar uma hierarquia visual consistente.

| Elemento | Tamanho |
|---|---:|
| **Small** | 14px |
| **Parágrafo** | 16px |
| **H5** | 18px |
| **H4** | 24px |
| **H3** | 28px |
| **H2** | 34px |
| **H1** | 40px |

### Hierarquia

```text
H1 — 40px
H2 — 34px
H3 — 28px
H4 — 24px
H5 — 18px
Parágrafo — 16px
Small — 14px
````

---

 ## ♿ Contraste

 O Design System apresenta diferentes combinações entre cores de fundo e texto para auxiliar na construção de interfaces com boa legibilidade.

 ### Exemplos

 - **Light + Primary**
- **Primary + Light**
- **Dark + Primary**

 As combinações devem ser avaliadas durante a implementação para garantir uma boa experiência de leitura e atender aos requisitos de acessibilidade do produto.

---

 ## 🧩 Design Tokens

 As cores podem ser transformadas em **Design Tokens** para facilitar sua utilização no desenvolvimento.

 ### CSS

```
:root {
  /* Primary */
  --color-primary-dark: #CC4E00;
  --color-primary: #FF6200;
  --color-primary-light: #FF8133;

  /* Secondary */
  --color-secondary-light: #539AE9;
  --color-secondary: #267FE3;
  --color-secondary-dark: #1866BE;

  /* Dark */
  --color-dark-light: #403B3B;
  --color-dark: #262323;
  --color-dark-dark: #0B0A0A;

  /* Light */
  --color-light-light: #FFFFFF;
  --color-light: #F2F5F7;
  --color-light-dark: #D3DDE4;

  /* Success */
  --color-success-light: #7BE085;
  --color-success: #52D65F;
  --color-success-dark: #2FC63E;

  /* Danger */
  --color-danger-dark: #9E1500;
  --color-danger: #D11C00;
  --color-danger-light: #FF2705;
}
```

---

 ## 📂 Estrutura do projeto

 Uma possível organização para o Design System:

```
design-system/
│
├── README.md
│
├── assets/
│   └── logo.png
│
├── tokens/
│   ├── colors.css
│   └── typography.css
│
├── components/
│   ├── button/
│   ├── input/
│   ├── card/
│   └── modal/
│
└── docs/
    └── guidelines.md
```

---

 ## 🎯 Objetivos

 O Design System tem como principais objetivos:

 - Manter a consistência visual das interfaces;
- Facilitar a criação de novos componentes;
- Reduzir decisões repetitivas durante o desenvolvimento;
- Centralizar cores e estilos;
- Melhorar a experiência do usuário;
- Facilitar a manutenção do projeto;
- Incentivar boas práticas de acessibilidade.

---

 ## 🛠️ Tecnologias

 - **HTML**
- **CSS**
- **Poppins**
- **Design Tokens**
- **Git**
- **GitHub**

---

 ## 🚀 Utilização

 Para utilizar os tokens de cores no CSS:

```
.button {
  background-color: var(--color-primary);
  color: var(--color-light-light);
}

.button:hover {
  background-color: var(--color-primary-dark);
}
```

---

 ## 📋 Status

 🟢 **Em desenvolvimento**

 Novos componentes, tokens e guidelines podem ser adicionados conforme a evolução do Design System.

---

 ## 📄 Licença

 Este projeto é destinado a fins de estudo, documentação e desenvolvimento de interfaces.

---

 \<p align="center"\> 🎨 \<strong\>Design System\</strong\> • Tipografia • Cores • Acessibilidade \</p\> \`\`\` **Observação:** para a imagem aparecer no GitHub, coloque o arquivo `Guilherme felix.png` na mesma pasta do `README.md`.
