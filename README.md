# PlayLife — Atividade Prática: Bootstrap e Tailwind CSS

## 1. Sobre o projeto

O projeto PlayLife foi desenvolvido para a atividade prática de Front-end, com o objetivo de experimentar e comparar dois frameworks CSS: **Bootstrap** e **Tailwind CSS**.

A proposta consiste em desenvolver duas versões de uma mesma página web, mantendo os mesmos elementos, conteúdos e organização visual, mas utilizando as ferramentas de estilização de cada framework.

Para o desenvolvimento, foi escolhido o tema de uma loja fictícia de jogos eletrônicos, com destaque para títulos populares como Minecraft, Mortal Kombat e Mario Kart.

## 2. Objetivos

- Praticar a construção de páginas web utilizando Bootstrap e Tailwind CSS.
- Compreender as diferenças entre as classes e as formas de estilização dos frameworks.
- Reproduzir o mesmo layout utilizando duas abordagens distintas.
- Comparar a organização do HTML, a facilidade de personalização e a experiência de desenvolvimento.
- Aplicar conceitos de responsividade para adaptar a página a diferentes tamanhos de tela.

## 3. Tecnologias utilizadas

- **HTML5:** estruturação do conteúdo das páginas.
- **Bootstrap 5:** construção do layout, organização das colunas, espaçamentos e estilização dos elementos na primeira versão.
- **Tailwind CSS:** estilização por meio de classes utilitárias na segunda versão.
- **Git e GitHub:** controle de versão, organização das branches e armazenamento do projeto.

## 4. Estrutura do repositório

O repositório está organizado de acordo com as orientações da atividade:

```text
PlayLife/
├── bootstrap/
│   ├── index.html
│   └── imagens/
├── tailwind/
│   ├── index.html
│   └── imagens/
├── README.md
└── analise-critica.docx
```

A pasta `bootstrap/` contém a versão desenvolvida com Bootstrap, enquanto a pasta `tailwind/` contém a versão desenvolvida com Tailwind CSS.

As pastas `imagens/` armazenam os arquivos visuais utilizados nas páginas, quando aplicável. O arquivo `README.md` apresenta a documentação do projeto, e o documento de análise crítica registra a comparação entre as tecnologias.

## 5. Organização das branches

O projeto utiliza três branches principais:

- **bootstrap:** desenvolvimento da página utilizando Bootstrap.
- **tailwind:** desenvolvimento da página utilizando Tailwind CSS.
- **main:** versão final do projeto, contendo as pastas `bootstrap/` e `tailwind/`, além deste README.

As duas implementações devem manter a mesma estrutura visual e o mesmo conteúdo, permitindo comparar diretamente as tecnologias.

## 6. Descrição das páginas

A página PlayLife representa uma loja fictícia de jogos eletrônicos.

O layout é composto por:

1. **Banner principal:** imagem de destaque com o nome PlayLife.
2. **Apresentação da loja:** título, texto introdutório e imagem principal.
3. **Conteúdo descritivo:** textos sobre o universo dos jogos eletrônicos.
4. **Seção de jogos em destaque:** três colunas dedicadas a Minecraft, Mortal Kombat e Mario Kart, com imagens, descrições e botões para conhecer cada jogo.

O layout foi planejado para se adaptar a diferentes tamanhos de tela, mantendo as três colunas lado a lado em telas maiores e organizando os conteúdos verticalmente em dispositivos menores.

## 7. Como executar o projeto

### Pré-requisitos

- Um navegador atualizado, como Google Chrome, Microsoft Edge ou Firefox.
- Git, caso deseje clonar o repositório.
- Um editor de código, como Visual Studio Code.

### Executando localmente

1. Clone o repositório:

   ```bash
   git clone URL_DO_REPOSITORIO
   ```

2. Acesse a pasta do projeto:

   ```bash
   cd PlayLife
   ```

3. Abra a pasta `bootstrap/` ou `tailwind/`.

4. Abra o arquivo `index.html` no navegador.

Também é possível abrir a pasta do projeto no Visual Studio Code e utilizar a extensão Live Server para visualizar as páginas durante o desenvolvimento.

**Observação:** substitua `URL_DO_REPOSITORIO` pelo endereço real do repositório no GitHub.

### Dependências

A versão Bootstrap utiliza o framework disponibilizado por CDN. A versão Tailwind deve ser executada conforme a configuração adotada em seu projeto. Caso utilize CDN para o Tailwind, será necessária conexão com a internet para carregar os recursos externos.

As imagens também devem estar disponíveis localmente ou em URLs acessíveis para que sejam exibidas corretamente.

## 8. Comparação entre as tecnologias

O Bootstrap disponibiliza componentes e classes predefinidas que facilitam a construção de layouts responsivos, como containers, linhas, colunas e botões.

O Tailwind CSS utiliza classes utilitárias que permitem configurar diretamente no HTML propriedades como cores, espaçamentos, dimensões e alinhamentos.

A implementação da mesma página nas duas tecnologias permite observar diferenças na escrita das classes, na organização do código, na personalização visual e na experiência de desenvolvimento.

A análise crítica complementar apresenta as observações realizadas durante a construção das duas versões, incluindo dificuldades encontradas, soluções adotadas, vantagens e limitações percebidas.

## 9. Considerações finais

A atividade proporciona uma experiência prática com dois frameworks amplamente utilizados no desenvolvimento de interfaces web.

Ao reproduzir a mesma página com Bootstrap e Tailwind CSS, é possível compreender diferentes abordagens de estilização e avaliar como cada tecnologia contribui para a construção de layouts responsivos e personalizados.

O projeto também reforça a utilização do Git e do GitHub para organizar versões do código, trabalhar com branches e documentar o desenvolvimento.

---

**Projeto acadêmico:** Atividade prática de Front-end — Bootstrap e Tailwind CSS.

**Tema:** Loja fictícia de jogos eletrônicos — PlayLife.
