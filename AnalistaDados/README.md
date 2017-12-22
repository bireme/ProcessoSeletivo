# Teste para preenchimento de vaga de analista de dados na BIREME/OPAS/OMS
Obrigado pelo seu interesse de fazer parte da equipe da [BIREME/OPAS/OMS](http://www.paho.org/bireme).

Realize as atividades descritas nos itens A, B, C e D.
## A. CRIAÇÃO DA CONTA NO GITHUB
1. Crie ou utilize sua conta no Github.
1. Faça um fork [deste repositório](https://github.com/bireme/ProcessoSeletivo).
## B. LIMPEZA DE BASE DE DADOS
1. Com os dados do [*AnalistaDados/proc_sel_db_ad.txt*](https://github.com/bireme/ProcessoSeletivo/blob/master/AnalistaDados/proc_sel_db_ad.txt), realizar processo de "Qualidade de Dados" que você considere adequado, seguindo as etapas de análise (data profiling), limpeza (data cleansing), normalização (data standardization), deduplicação e melhoria (data enrichment).
1. Documentar as etapas utilizadas assim como a justificativa para a utilização das mesmas. Mencione se você utilizou alguma ferramenta específica de qualidade de dados. Armazenar a documentação no arquivo *AnalistaDados/dataqualitydoc.md*.
1. Criar uma base de dados MySQL com os dados resultantes do processo descrito no ítem anterior.
1. Criar o arquivo dump da base gerada e armazená-lo em *AnalistaDados/sqldumpdq.sql*
## C. CRIAÇÃO DE WEB SERVICE
1. Criar um serviço web como descrito abaixo.
1. Utilizar umas das seguintes linguagens de programação: Java ou Python.
1. Criar documentação explicando o processo de instalação do serviço web criado e armazená-la no arquivo *AnalistaDados/webservice/*
1. Disponibilizar no diretório *AnalistaDados/webservice/* todos os códigos-fonte deste serviço.
1. O serviço web deve obedecer o seguinte padrão de url: `http://<host>/<githubuser>/<coluna>/<expressao_busca>`. O parâmetro <coluna> é a identificação da coluna do arquivo proc_sel_db_ad.txt. O parâmetro <expressao_busca> é uma expressão de busca que será aplicada na coluna correspondente. O nível de tratamento dado na expressão de busca será considerando um diferencial positivo na avaliação do candidato. Por exemplo, tratamento simples: busca por uma palavra, tratamento avançado: busca booleana.
1. A saída do serviço deve ser um arquivo JSON contendo o total de registros recuperados na busca e os dados de cada um destes registros.
1. O uso da biblioteca Apache Lucene e de framework web para construção da solução será considerado um diferencial positivo na avaliação do candidato.
## D. NOTIFICAÇÃO PARA AVALIAÇÃO DO TESTE
1. Preencher o formulário disponível em https://goo.gl/forms/LYAem5hDTQPJiE0F3
1. Aguardar contato para as próximas etapas do processo seletivo (análise de currículo e entrevistas)
