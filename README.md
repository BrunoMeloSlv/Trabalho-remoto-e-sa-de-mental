# Análise de Estresse no Ambiente de Trabalho

Este projeto visa analisar os níveis de estresse de funcionários em diferentes setores e condições de trabalho. Utilizando diversos testes estatísticos e técnicas de machine learning, buscamos entender quais fatores estão associados ao aumento ou redução do estresse no ambiente corporativo.

## Descrição do Projeto

O foco deste estudo está em explorar como diferentes variáveis, como tipo de trabalho (remoto, presencial, híbrido), condições de saúde mental e benefícios como plano de saúde, podem influenciar os níveis de estresse dos funcionários. Foram aplicados testes de correlação, modelos de regressão e análises de proporções para responder às questões propostas pelos gestores.

### Ferramentas Utilizadas

- **Python**: Para análise de dados e implementação dos testes estatísticos.
- **Pandas**: Manipulação e filtragem de dados.
- **Statsmodels**: Testes de regressão logística multinomial e cálculo de estatísticas Z.
- **Matplotlib e Seaborn**: Visualização de dados por meio de gráficos.
- **Scikit-learn**: Codificação de variáveis categóricas e análise de dados.

## Principais Análises Realizadas

1. **Correlação entre Idade, Tipo de Trabalho e Estresse**: Um modelo de regressão logística multinomial foi utilizado para verificar se as variáveis preditoras têm um impacto significativo no nível de estresse. Resultado: Não há impacto significativo.

2. **Teste Z para Comparar Proporções**: 
   - Analisamos a proporção de pessoas com problemas de saúde mental e sem, verificando se há diferença nos níveis de estresse. Resultado: Não há diferença significativa.
   - Comparamos funcionários com e sem plano de saúde. Resultado: Diferença significativa nos níveis de estresse.

3. **Conversão de Variáveis Categóricas**: Para o modelo de regressão, utilizamos a técnica de One-Hot Encoding para transformar variáveis como tipo de trabalho em binárias.

## Instruções de Uso

1. Clone o repositório:
   ```bash
   git clone [https://github.com/SEU_USUARIO/nome-do-repositorio.git](https://github.com/BrunoMeloSlv/Trabalho-remoto-e-sa-de-mental)
   
