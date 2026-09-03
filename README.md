# CP_SERS_Analise_Dados_Energia

## Integrantes:

Gabriela Silva - RM: 570808  
Izabelly Menezes - RM: 570673  
Marcos Sampaio - RM: 573987  
Otávio Santos - RM: 570225  
Tiago Muhlmann - RM: 569569  
Wesley Marques - RM: 573915  

## Descrição do trabalho

Este trabalho consiste em uma análise exploratória de dados de carga elétrica verificada da área SP, obtidos via API pública do ONS (Operador Nacional do Sistema Elétrico), cobrindo o período de 01 a 07/08/2025 (336 medições em intervalos de 30 minutos).

A partir dos dados brutos retornados pela API, a equipe construiu e organizou um DataFrame, calculou indicadores estatísticos (mínima, máxima, média, mediana e amplitude), identificou períodos de alta demanda (>90% da carga máxima) e aplicou um segundo critério de recorte (carga acima da média), comparando os dois grupos resultantes. Os resultados foram ilustrados em gráficos de série temporal e de distribuição (histograma), e sintetizados em indicadores que serviram de base para a geração de um relatório técnico com apoio de um modelo de linguagem (Gemini).

Por fim, o trabalho inclui uma etapa de **validação crítica**: o texto gerado pela IA foi comparado ponto a ponto com os cálculos e gráficos produzidos pela equipe, identificando afirmações não sustentadas pelos dados (como atribuições causais sem evidência e uma leitura equivocada de tendência de crescimento) e comparações estatísticas imprecisas entre os dois critérios de recorte. Essas falhas foram corrigidas em um relatório final revisado, que mantém apenas as conclusões diretamente sustentadas pelos dados, separando claramente observação de hipótese.

## Fontes

Portal: https://dados.ons.org.br/
Conjunto de dados: https://dados.ons.org.br/dataset/carga-energia-verificada
