# Classificação de Risco de Crédito

Projeto de ciência de dados desenvolvido no curso Profissão: Cientista de Dados da EBAC. O notebook explora dados cadastrais e constrói uma análise para identificar clientes com maior risco de inadimplência.

## Objetivo

Investigar a relação entre características do cliente e a variável `mau`, que identifica o histórico de bom ou mau pagador.

## Conteúdo

- análise exploratória e tratamento dos dados;
- avaliação de variáveis cadastrais;
- preparação da variável-alvo;
- modelagem e interpretação dos resultados.

## Dataset

O arquivo `demo01.csv` contém dados anonimizados. As principais variáveis são sexo, idade, tipo de renda, escolaridade, estado civil, posse de imóvel e veículo, tempo de emprego e quantidade de pessoas na residência.

A variável-alvo é:

| Campo | Significado |
|---|---|
| `mau` | `true` para mau pagador e `false` para bom pagador |

## Executar localmente

```bash
git clone https://github.com/EduardoQuero/Credit-score.git
cd Credit-score
python -m venv .venv
```

Ative o ambiente virtual e instale as dependências usadas no notebook:

```bash
pip install jupyter pandas numpy matplotlib seaborn scikit-learn
jupyter notebook
```

Abra `Projeto 01 - Classificacao de credito - Eduardo Quero.ipynb` e execute as células em ordem.

## Arquivos

```text
Projeto 01 - Classificacao de credito - Eduardo Quero.ipynb
demo01.csv
README.md
```

> Projeto educacional. Os resultados não devem ser usados isoladamente para decisões reais de crédito.