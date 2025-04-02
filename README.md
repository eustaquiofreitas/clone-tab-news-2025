# Criação do Projeto - Fundação (Clone TabNews) 2025

## 1 - Criando o repositório no Git Hub;

- Criando a Milestone - _Milestone 1 Fundação_;
[ Teste Automatizados ]

src
├── components   # Componentes globais de uso geral do projeto.
├── layout       # Wrappers padrões para componentes ou páginas.
├── hooks        # Hooks globais de uso geral do projeto.
├── contexts     # Contexts para gerenciamento de estado global do projeto.
├── modules      # Módulos. Um para cada página, com a lógica de negócio.
│      └──   example-module
│              ├──  index.js/ts  # Ponto de partida desse módulo. Esse arquivo será importado na página pertinente.
│              ├──  hooks        # Hooks globais de uso exclusivo desse módulo.
│              ├──  components   # Componentes de uso exclusivo desse módulo.
│              ├──  service      # Funções e lógicas de utilização geral e genérica de uso exclusivo desse módulo.
│              └──  utils        # Componentes de uso exclusivo desse módulo.
├── pages        # Cada página associada com uma rota e um módulo. 
├── services     # Lógica de comunicação com o backend.
├── shared       # Tudo que for compartilhável entre módulos. Sendo configuração de temas, etc.
└── utils        # Funções e lógicas de utilização geral e genérica.
