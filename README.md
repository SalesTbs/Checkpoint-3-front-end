# 🔥 Lume | Isqueiros de Luxo

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css&logoColor=white)
![Google Fonts](https://img.shields.io/badge/Google_Fonts-4285F4?style=for-the-badge&logo=googlefonts&logoColor=white)
![Font Awesome](https://img.shields.io/badge/Font_Awesome-528DD7?style=for-the-badge&logo=fontawesome&logoColor=white)
![FIAP](https://img.shields.io/badge/FIAP-Engenharia_de_Software-red?style=for-the-badge)
[![Deploy](https://img.shields.io/badge/Acessar_Projeto-007ACC?style=for-the-badge&logo=vercel&logoColor=white)](LINK_DO_DEPLOY_AQUI)
[![Repositório](https://img.shields.io/badge/Repositório-000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/SalesTbs/Checkpoint-3-front-end)

Landing page conceitual de uma boutique de isqueiros de luxo, desenvolvida para a atividade **Checkpoint 3** da disciplina de **Front-End Design** do curso de **Engenharia de Software** na **FIAP**. A proposta é apresentar uma vitrine digital com estética sofisticada, conteúdo editorial sobre a marca e seus produtos, orientações de conservação e uma seção de perguntas frequentes.

> **Tipo de projeto:** site estático desenvolvido com HTML5 e CSS3, sem JavaScript.

## 🔗 Links do projeto

- **Repositório no GitHub:** [Checkpoint-3-front-end](https://github.com/SalesTbs/Checkpoint-3-front-end)
- **Site publicado:** [Lume | Isqueiros de Luxo](https://github.com/SalesTbs/Checkpoint-3-front-end)

## 📌 Sobre o Projeto

O projeto consiste em uma *landing page* para a **Lume**, uma marca conceitual de isqueiros de luxo. A página apresenta uma coleção de produtos e destaca a tradição, a sofisticação e os cuidados relacionados às peças, com uma identidade visual baseada em tons escuros e detalhes dourados.

O enunciado do Checkpoint 3 propõe a criação de uma página com design próprio e tema livre, estruturada como uma vitrine para apresentar um produto. A Lume foi desenvolvida para atender a essa proposta por meio de uma página institucional e comercial conceitual.

Entre os recursos presentes no projeto, estão:

* Estruturação do conteúdo com **HTML5** e uso de elementos como `header`, `section` e `footer`.
* Estilização em um arquivo **CSS externo**, vinculado ao HTML.
* Navegação entre seções por meio de links internos e identificadores (`id`).
* Organização do layout com **Flexbox**.
* Uso de variáveis CSS e classes reutilizáveis para manter consistência visual.
* Apresentação de informações sobre produtos, marca, autenticidade e manutenção.
* Seção de perguntas frequentes construída com os elementos nativos `details` e `summary` do HTML.

## 🖼️ Imagens Utilizadas no Projeto

O projeto utiliza imagens ilustrativas para acompanhar as seções de conteúdo:

<div align="center">
  <img src="./imagens/imagem%201.jfif" alt="Isqueiro de luxo sobre a mesa" width="400px"/>
</div>
<div align="center">
  <img src="./imagens/imagem%202.jfif" alt="Isqueiro de luxo com a chama acesa" width="400px"/>
</div>
<div align="center">
  <img src="./imagens/imagem%203.jfif" alt="Acessório para limpeza de isqueiro de luxo" width="400px"/>
</div>
<div align="center">
  <img src="./imagens/imagem%204.jfif" alt="Isqueiro preto de luxo" width="400px"/>
</div>

## 🗂️ Estrutura da Página

A página possui **oito seções de conteúdo**, sem contar o menu e o rodapé, atendendo ao requisito do enunciado de no mínimo quatro seções distintas:

1. **Apresentação inicial:** título “O Domínio da Chama” e texto introdutório da marca.
2. **Nossa Coleção:** cards com três modelos de isqueiros — Monolito, Aura Dourada e Eclipse — acompanhados de preços e descrições.
3. **Sobre a marca:** conteúdo institucional sobre a história, a tradição e a proposta da Lume.
4. **A Arte do Fogo:** texto sobre o simbolismo do fogo e a proposta estética dos produtos.
5. **O Legado do Luxo:** conteúdo sobre tradição, materiais e acabamento das peças.
6. **Autenticidade e Exclusividade:** informações sobre procedência, certificação e exclusividade.
7. **Cuidados e Manutenção:** recomendações para conservação dos isqueiros.
8. **Perguntas Frequentes (FAQ):** respostas sobre recarga, garantia, tipos de chama e envio dos produtos.

O **cabeçalho** contém o logotipo Lume e links de navegação para Coleção, Sobre, Conhecimento e FAQ. O **rodapé** reúne informações de contato, links para redes sociais e direitos autorais.

## 🌐 Tecnologias e recursos externos

| Tecnologia / recurso | Uso no projeto |
| --- | --- |
| HTML5 | Estrutura e conteúdo da página. |
| CSS3 | Identidade visual, estilos, espaçamento e layout. |
| Flexbox | Alinhamento do cabeçalho, navegação, cards de produtos, blocos editoriais e rodapé. |
| [Google Fonts](https://fonts.google.com/) | Fontes **Playfair Display** e **Inter**. |
| [Font Awesome](https://fontawesome.com/) | Ícones de contato e redes sociais, carregados pela CDN Font Awesome 6.5.1. |
| Imagens locais | Imagens ilustrativas armazenadas na pasta `Projeto/imagens/`. |

As fontes do Google Fonts e os ícones do Font Awesome são carregados por serviços externos; por isso, esses recursos dependem de conexão com a internet. O site não utiliza bibliotecas JavaScript nem requer instalação de dependências.

## 🎨 Style Guide e Design System

Para atender ao requisito de padronização visual do Checkpoint 3, o arquivo `css/style.css` documenta um **Style Guide** no início do código e define variáveis CSS em `:root`. Esses tokens centralizam a paleta de cores e ajudam a manter a identidade visual consistente entre as seções.

### Paleta de cores

| Aplicação | Cor | Variável CSS |
| --- | --- | --- |
| Fundo principal | `#111111` | `--c-bg` |
| Fundo de cards | `#1b1b1b` | `--c-bgcard` |
| Bordas e divisórias | `#2a2a2a` | `--c-border` |
| Destaques dourados | `#b8913f` | `--c-gold` |
| Texto principal | `#f2ede4` | `--c-text` |
| Texto secundário | `#a8a29a` | `--c-text2` |

### Tipografia

| Uso | Fonte | Aplicação |
| :--- | :--- | :--- |
| Títulos | [Playfair Display](https://fonts.google.com/specimen/Playfair+Display) | Usada nos títulos e no logotipo para reforçar a identidade clássica com estilo serifado. |
| Textos | [Inter](https://fonts.google.com/specimen/Inter) | Usada nos parágrafos, navegação e demais textos para manter a leitura clara. |

As duas fontes são importadas do **Google Fonts** no `index.html`.

### Componentes

* **Classes reutilizáveis:** `.container` centraliza o conteúdo e limita sua largura; `.section-padding` padroniza o espaçamento vertical das seções; `.section-title` centraliza e padroniza títulos de seção.
* **Flexbox:** aplicado em elementos como `.header-content`, `.hero`, `.products-grid`, `.content-row`, `.footer-grid` e `.social-links` para alinhar e distribuir os conteúdos.
* **Interações visuais:** transições e efeitos de *hover* destacam links, cards e elementos interativos.
* **Ícones:** a biblioteca **Font Awesome** é utilizada para ícones de contato e redes sociais no rodapé.

### Diretrizes de layout

- Containers centralizados com largura máxima definida.
- Flexbox para organizar os principais grupos de conteúdo.
- Espaçamento vertical consistente entre seções.
- Dourado reservado para destaques, preços, detalhes do logotipo e estados de interação.
- Fundo escuro e tons neutros usados de forma consistente ao longo da página.

## 📁 Estrutura de Arquivos

```text
Checkpoint-3-front-end/
├── index.html
├── integrantes.txt
├── css/
│   └── style.css
├── imagens/
│   ├── favicon.png
│   ├── imagem 1.jfif
│   ├── imagem 2.jfif
│   ├── imagem 3.jfif
│   └── imagem 4.jfif
└── README.md
```

- `index.html`: marcação e conteúdo da página.
- `css/style.css`: variáveis do design system e estilos de todos os componentes.
- `imagens/`: favicon e imagens ilustrativas referenciadas no HTML.
- `integrantes.txt`: relação de integrantes e respectivos RMs.

## 🚀 Como Executar o Projeto

O projeto utiliza HTML e CSS, sem necessidade de instalar dependências por meio do npm.

1. **Clone o repositório:**
   ```bash
   git clone https://github.com/SalesTbs/Checkpoint-3-front-end.git
   ```

2. **Acesse a pasta do projeto:**
   ```bash
   cd Checkpoint-3-front-end
   ```

3. **Abra a página:**
   * Abra o arquivo `index.html` diretamente no navegador; ou
   * Se estiver utilizando o **Visual Studio Code**, execute a página com a extensão **Live Server**.

Mantenha a estrutura de pastas e os nomes dos arquivos de imagem para que os caminhos definidos no HTML continuem funcionando.

> **Observação:** As fontes do Google Fonts e os ícones do Font Awesome são carregados por serviços externos. Para que esses recursos sejam exibidos corretamente, é necessário ter conexão com a internet.

## Relação com os requisitos do Checkpoint 3

| Requisito da atividade | Como aparece no projeto |
| --- | --- |
| Estrutura HTML5 | Página principal em `Projeto/index.html`, com conteúdo organizado em elementos HTML. |
| Uso de `class` e `id` | Classes reutilizáveis para layout e componentes; IDs usados para identificar seções e permitir a navegação por âncoras. |
| Pastas organizadas | HTML, CSS, imagens e arquivo de integrantes separados conforme a estrutura do projeto. |
| CSS externo | `Projeto/css/style.css` é vinculado ao HTML por meio de `link`. |
| Google Fonts | Importação de Playfair Display e Inter. |
| Imagens e ícones | Imagens locais e ícones da biblioteca Font Awesome. |
| Pelo menos quatro seções de conteúdo | A página contém as seções de coleção, sobre, arte do fogo, legado, autenticidade, manutenção e FAQ, além da apresentação inicial. |
| Flexbox | Utilizado para posicionamento e alinhamento de diversos grupos de elementos. |
| Style Guide e Design System | Paleta, variáveis de cor e tipografia documentadas no CSS. |
| Colaboração | O grupo listado possui cinco integrantes, dentro do limite indicado na atividade. |


## 👥 Desenvolvedores

<div align="center">

| Integrante | RM | GitHub |
| :--- | :---: | :---: |
| **David Manoel Barros Pereira** | `RM576915` | [@davidm-dk](https://github.com/davidm-dk) |
| **Guilherme Andrade Dos Santos Trevisan** | `RM576676` | [@zztrevisan](https://github.com/zztrevisan) |
| **João Victor Matos de Almeida** | `RM574928` | [@L1nguin3](https://github.com/L1nguin3) |
| **Lucas dos Santos Gomes** | `RM576912` | [@lucas-dos-santos-gomes](https://github.com/lucas-dos-santos-gomes) |
| **Thales Bernardino Seixas** | `RM574617` | [@SalesTbs](https://github.com/SalesTbs) |

</div>

---

<div align="center">
  <p>Desenvolvido como projeto acadêmico para o <b>Checkpoint 3 — Front-end</b>.</p>
</div>