# Pokédex — Atividade 03

Projeto de Desenvolvimento e Integração de Aplicações Web (DIAW), da PUC Minas.

**Aluno:** Bernardo Machado Ribeiro

## Sobre

Fiz uma Pokédex com React para pesquisar Pokémon, conferir seus atributos e ver as equipes dos treinadores. Também dá para marcar favoritos, filtrar por tipo e sortear um Pokémon.

## Como executar

Precisa ter o Node.js instalado. No terminal, dentro da pasta do projeto:

```bash
npm install
npm run dev
```

Depois é só abrir o endereço mostrado pelo Vite, normalmente http://localhost:5173.

Para gerar a versão de produção:

```bash
npm run build
```

## Organização

- `src/data/pokedex-data.json`: arquivo de dados fornecido pelo professor, com Pokémon, tipos e treinadores.
- `src/components/`: cards, filtros, detalhes e área de treinadores.
- `src/App.jsx`: tela principal, pesquisa, favoritos e navegação.
- `src/style.css`: visual e responsividade.

## Funcionalidades

- Lista dos Pokémon do arquivo original
- Busca por nome e ID, com atualização enquanto digita
- Filtro por tipo e ordenação por atributos
- Seis atributos nos cards e nos detalhes
- Treinadores com insígnias e equipes
- Favoritos salvos no navegador
- Pokémon aleatório e modo claro/escuro
- Layout para celular e computador

As informações vêm do JSON da atividade, sem precisar de banco de dados ou de uma API para carregar os Pokémon. As **imagens** são carregadas do repositório público de sprites da PokéAPI: https://github.com/PokeAPI/sprites.
