# Classificação de Risco de Crédito

Projeto de ciência de dados que investiga características associadas à inadimplência e estrutura um fluxo analítico para classificação de risco.

## Problema

Bases cadastrais podem conter sinais úteis para compreender perfis de pagamento. O projeto explora essas relações, prepara os dados e analisa a variável-alvo `mau`.

| Valor | Interpretação |
|---|---|
| `true` | Mau pagador |
| `false` | Bom pagador |

## Valor para o negócio

A análise permite demonstrar como dados podem apoiar:

- identificação de padrões de inadimplência;
- segmentação de perfis de risco;
- priorização de análises;
- interpretação das variáveis mais relevantes;
- construção de processos analíticos reproduzíveis.

> Projeto educacional. Os resultados não devem ser utilizados isoladamente para aprovar, negar ou precificar crédito.

## Etapas do projeto

```mermaid
flowchart LR
    A[Dados anonimizados] --> B[Qualidade dos dados]
    B --> C[Análise exploratória]
    C --> D[Preparação]
    D --> E[Modelagem]
    E --> F[Interpretação]
```

## Competências demonstradas

- limpeza e tratamento de dados com Pandas;
- análise exploratória e visualização;
- preparação da variável-alvo;
- modelagem de classificação;
- interpretação de resultados;
- documentação técnica.

## Dataset

O arquivo `demo01.csv` contém dados anonimizados para fins educacionais. Entre as variáveis estão sexo, idade, tipo de renda, escolaridade, estado civil, posse de imóvel e veículo, tempo de emprego e quantidade de pessoas na residência.

## Estrutura

```text
Projeto 01 - Classificacao de credito - Eduardo Quero.ipynb
demo01.csv
README.md
```

## Executar localmente

```bash
git clone https://github.com/EduardoQuero/Credit-score.git
cd Credit-score
python -m venv .venv
```

Ative o ambiente e execute:

```bash
pip install jupyter pandas numpy matplotlib seaborn scikit-learn
jupyter notebook
```

Abra `Projeto 01 - Classificacao de credito - Eduardo Quero.ipynb` e execute as células em ordem.

## Dados e confidencialidade

O repositório utiliza dados anonimizados e não contém informações de empregadores, clientes, credenciais ou regras internas.

## Autor

[Eduardo Quero](https://www.linkedin.com/in/eduardo-quero/)