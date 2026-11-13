# Estruturas de Programação em Python

Coleção didática de exemplos e exercícios introdutórios sobre decisões, repetições e funções em Python.

## Conteúdo

- Estruturas condicionais com `if`, `elif` e `else`.
- Laços com `while` e `for`.
- Uso de `range`, listas, acumuladores e médias.
- Declaração de funções, parâmetros, retorno e escopo.
- Exercícios separados por assunto.
- Um `main.py` que reúne diferentes exemplos.

## Arquivos principais

| Arquivo | Conteúdo |
| --- | --- |
| `Estrutura_de_decisão.py` | Exemplos de estruturas condicionais |
| `Ex_Estru_decisão.py` | Exercícios de decisão |
| `Estrutua_de_repetiçao.py` | Exemplos com `for` e `while` |
| `Ex_Estru_repetição.py` | Exercícios de repetição |
| `Funções.py` | Exemplos de funções |
| `Ex_Funções.py` | Exercícios com funções |
| `main.py` | Execução conjunta dos módulos |

## Como executar

O projeto foi criado para Python 3.8 e possui configuração do Poetry.

```bash
poetry install
poetry run python main.py
```

Também é possível executar cada arquivo separadamente:

```bash
python Estrutura_de_decisão.py
python Estrutua_de_repetiçao.py
python Funções.py
```

Alguns exemplos são interativos e solicitam valores pelo terminal.

## Observação

O ambiente virtual não faz parte do repositório. Cada pessoa deve criar o próprio ambiente usando Poetry, `venv` ou outra ferramenta de preferência.
