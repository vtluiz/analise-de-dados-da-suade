# Análise de Dados de Saúde

Este projeto visa analisar e visualizar dados de saúde para entender a relação entre idade, índice de massa corporal (BMI), e custos de saúde, com uma atenção especial ao status de fumante. O projeto inclui a criação de gráficos de dispersão que ilustram a relação entre as variáveis.

## Estrutura do Projeto

- `src/`: Contém o código-fonte para análise e visualização dos dados.
- `README.md`: Este arquivo com informações sobre o projeto.
- `.gitignore`: Arquivo para especificar quais arquivos e pastas devem ser ignorados pelo Git.

## Dados

O dataset inclui as seguintes colunas:
- `age`: Idade do indivíduo.
- `sex`: Gênero do indivíduo (male ou female).
- `bmi`: Índice de Massa Corporal (BMI).
- `children`: Número de crianças dependentes.
- `smoker`: Indica se o indivíduo é fumante (yes ou no).
- `region`: Região geográfica do indivíduo.
- `charges`: Custos de saúde.

## Dependências

Este projeto utiliza as seguintes bibliotecas Python:
- `pandas`
- `matplotlib`
- `seaborn`

Você pode instalar as dependências necessárias usando o `pip`:
```sh
pip install pandas matplotlib seaborn
