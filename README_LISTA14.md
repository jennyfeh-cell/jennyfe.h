# Lista 14 - Herança | Sistema de Agendamento de Serviços

Projeto baseado no material disponibilizado pelo professor Gilbert Azevedo da Silva.

## O que foi alterado

As classes `HorarioDAO`, `ServicoDAO`, `ProfissionalDAO` e `AtendimentoDAO` agora herdam da classe abstrata `DAO`, assim como `ClienteDAO`.

A classe `DAO` mantém os métodos comuns de inserir, listar, buscar por ID, atualizar e excluir. Cada classe filha implementa somente `_abrir()` e `_salvar()` para ler e gravar seu respectivo arquivo JSON.

## Como abrir no VSCode

1. Extraia esta pasta.
2. Abra a pasta `Lista14_Projeto_Agendamento` no VSCode.
3. Abra o terminal integrado.
4. Instale o Streamlit, caso ainda não esteja instalado:

   `python -m pip install streamlit`

5. Execute:

   `python -m streamlit run index.py`

Os arquivos JSON ficam na pasta principal do projeto.

## Diagramas

A pasta `diagramas` contém:
- `diagrama_casos_de_uso.puml`
- `diagrama_classes.puml`

São arquivos PlantUML. Para visualizar, use uma extensão PlantUML no VSCode ou um renderizador compatível.

## Observação

Os diagramas representam a estrutura e as funcionalidades identificadas nos arquivos do projeto. O diagrama de classes apresenta os principais atributos, métodos e relações entre as camadas.
