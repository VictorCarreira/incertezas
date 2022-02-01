# incertezas

# Repositório dedicado ao cálculo de incerteza de dados de poços 

    1. Discussão sobre quais dados e quais equações usar na análise de incertezas (e qual pacote)
        a. Estratégia 1 - dados de perfilagem - calcular o COT com o Passey - comparar com o Achilles no mesmo poço simulado. Aqui as incertezas são devidas ao método, aos dados de perfilagem, e as incertezas nas equações do  Achilles. Precisa dos dados de perfilagem.
        b. Estratégia 2 - comparar os dados PONTUAIS com extratos nas mesmas profundidades calculados pelo Achilles. Aqui as incertezas são devidas aos erros analíticos (poço) e as incertezas nas equações do Achilles. Precisa dos dados dos poços separadamente. Veja o item acima 5. Vamos usar estes.
        c. Lembrando que no site do Achilles só tem o 86A. E lembrando que temos dados de todos os poços para jogar no Achilles. Sugestão: rodar para todos os poços dentro da área de estudo.


## Conteúdo das subpastas:

    * entradas: contém os dados de entrada em formato .las e os dados que estão no Achilles
    * saidas: contém todo resultado de saída dos programas desde gráficos até dados
    * modulos: contém os módulos internos para execução dos programas
    * programas: contém os programas de monte carlo e incertezas
    * Antigo: contém resultados anteriores rodado no programa achilles 
