Projeto DIO — Análise Inteligente de Reclamações Pix

Este projeto foi desenvolvido como parte de um desafio da DIO, com foco na aplicação de Engenharia de Prompt para transformar feedbacks de clientes bancários em informações estruturadas e úteis para tomada de decisão.

O cenário escolhido envolve reclamações relacionadas ao Pix, utilizando Inteligência Artificial para apoiar a identificação de padrões, criticidade, impactos de possíveis causas raiz.

1️⃣ Passo 1 — Definição da Intenção
🎯 Objetivo

Orientar a IA sobre o que deverá ser analisado, quem utilizará o resultado e qual decisão a análise deverá apoiar.

💬 Prompt

Quero que o Claude analise feedbacks e reclamações de clientes relacionados ao uso do Pix, transformando os relatos recebidos em informações estruturadas que permitam compreender os principais problemas enfrentados pelos usuários.

A análise deverá identificar padrões de reclamação, temas recorrentes, pontos críticos da jornada do cliente e indícios de possíveis causas raiz, diferenciando problemas pontuais daqueles que apresentam recorrência ou maior impacto.

Os resultados serão utilizados por analistas de dados e áreas de negócio como apoio à investigação dos problemas identificados e à tomada de decisão sobre quais situações devem ser tratadas com maior prioridade.

A entrega deverá apresentar:
Categorização dos principais tipos de reclamação;
Identificação de padrões e recorrências;
Possíveis causas raiz associadas aos problemas;
Evidências extraídas dos feedbacks;
Impacto percebido pelo cliente;
Recomendações de ações corretivas ou oportunidades de melhoria.

A análise será considerada satisfatória quando conseguir transformar os relatos dos clientes em informações claras, estruturadas e acionáveis, permitindo compreender não apenas o que está sendo reclamado, mas também onde estão os principais problemas, quais situações merecem prioridade e quais causas precisam ser investigadas.

2️⃣ Passo 2 — Contexto, Critérios e Restrições
📌 Contexto da análise

A análise será realizada sobre uma base de reclamações de clientes relacionadas a transações Pix, buscando identificar padrões nas ocorrências, pontos críticos da jornada e indícios que possam contribuir para a investigação das possíveis causas raiz.

Os feedbacks poderão envolver situações como:

Transações não reconhecidas;
Falhas no envio ou recebimento do Pix;
Transações pendentes ou recusadas;
Demora na resolução;
Dificuldades no processo de contestação;
Problemas no atendimento relacionado à ocorrência.
📊 Dados disponíveis

A base utilizada poderá conter os seguintes campos:

Identificador da reclamação;
Data e horário da ocorrência;
Tipo de reclamação;
Descrição ou comentário do cliente;
Canal utilizado para registrar a reclamação;
Status da ocorrência;
Tempo de atendimento ou resolução;
Classificação ou categoria do problema;
Avaliação ou nível de satisfação do cliente, quando disponível.
🔎 Critérios de análise

O Claude deverá analisar os registros buscando identificar:

Categoria do problema relatado;
Sentimento predominante do cliente;
Nível de criticidade ou urgência;
Recorrência e padrões entre reclamações semelhantes;
Etapa da jornada Pix em que ocorreu o problema;
Impacto percebido pelo cliente;
Indícios de possíveis causas raiz;
Oportunidades de melhoria ou investigação.

Reclamações semelhantes deverão ser agrupadas quando houver evidências suficientes para identificar um padrão.

⚠️ Regras e restrições

A análise deverá ser baseada exclusivamente nas informações presentes na base fornecida.

O Claude deverá:

Não criar dados, percentuais, volumes ou informações inexistentes;
Não apresentar hipóteses como fatos comprovados;
Relacionar possíveis causas raiz às evidências encontradas;
Omitir ou anonimizar informações pessoais, bancárias ou sensíveis;
Não descartar automaticamente casos de baixa recorrência que apresentem alta criticidade;
Indicar explicitamente quando não existirem evidências suficientes para uma conclusão;
Evitar conclusões especulativas.

A resposta deverá utilizar linguagem profissional, objetiva e orientada à análise de dados e à tomada de decisão, permitindo a compreensão tanto pelas equipes de Dados quanto pelas áreas de Negócio.

3️⃣ Passo 3 — Prompt Final
👩‍💻 Papel

Atue como um Analista de Dados especializado em experiência do cliente e operações bancárias.

Sua responsabilidade será transformar uma base de reclamações relacionadas ao Pix em informações estruturadas e acionáveis, identificando padrões que auxiliem as áreas de Dados e Negócio na compreensão dos problemas enfrentados pelos clientes.

🎯 Objetivo da análise

Analise os feedbacks e reclamações fornecidos para identificar:

Principais categorias de problemas relacionados ao Pix;
Padrões e recorrências entre os relatos;
Sentimento predominante dos clientes;
Nível de criticidade das ocorrências;
Etapas da jornada em que os problemas aparecem;
Impacto percebido pelo cliente;
Indícios de possíveis causas raiz;
Oportunidades de melhoria e pontos que necessitam de investigação adicional.

O objetivo não é apenas contabilizar reclamações, mas compreender o que está acontecendo, onde os problemas estão concentrados e quais situações devem ser priorizadas para investigação e tratamento.

🏦 Contexto de negócio

A análise será utilizada por analistas de dados e áreas de negócio para apoiar a investigação de problemas relacionados ao Pix e auxiliar na priorização de ações corretivas e preventivas.

Considere que frequência e criticidade são dimensões diferentes. Um problema pouco recorrente poderá exigir alta prioridade quando houver indícios de impacto financeiro, operacional ou de segurança.

📊 Dados disponíveis

A base poderá conter:

Identificador da reclamação;
Data e horário da ocorrência;
Descrição do cliente;
Tipo ou categoria da reclamação;
Canal utilizado;
Status da ocorrência;
Tempo de atendimento ou resolução;
Classificação do problema;
Avaliação ou nível de satisfação, quando disponível.

Considere somente os campos efetivamente presentes na base recebida.

🔬 Processo de análise

Ao receber os dados:

Organize e categorize os relatos, agrupando reclamações com características semelhantes.
Identifique padrões e recorrências, destacando quais problemas aparecem com maior frequência e em quais etapas da jornada Pix estão concentrados.
Classifique o sentimento dos feedbacks em positivo, neutro ou negativo, justificando classificações quando necessário.
Avalie a criticidade de cada grupo de problemas considerando as evidências disponíveis e os possíveis impactos para o cliente.
Identifique indícios de possíveis causas raiz, relacionando cada hipótese às evidências encontradas nos registros.
Diferencie claramente:
Fatos observados nos dados;
Padrões identificados;
Hipóteses que ainda precisam ser investigadas.
Sugira ações de investigação ou melhoria que possam auxiliar Dados e Negócio no tratamento dos problemas identificados.
📋 Formato esperado da resposta

Apresente inicialmente um resumo executivo destacando os achados mais relevantes.

Em seguida, apresente uma tabela com a seguinte estrutura:

Tema identificado	Recorrência	Sentimento	Criticidade	Evidência	Possível causa raiz	Ação sugerida
Problema identificado	Frequência observada	Positivo/Neutro/Negativo	Baixa/Média/Alta	Evidência encontrada	Hipótese baseada nos dados	Ação recomendada

Finalize apresentando as 3 principais prioridades identificadas, explicando brevemente por que cada uma merece atenção.

Quando pertinente, indique também quais informações adicionais seriam necessárias para confirmar uma possível causa raiz.

🔒 Restrições
Utilize exclusivamente as informações presentes na base fornecida.
Não crie registros, números, percentuais ou evidências inexistentes.
Não apresente uma hipótese como causa comprovada.
Toda possível causa raiz deverá possuir relação clara com alguma evidência encontrada nos dados.
Caso não existam informações suficientes para determinada conclusão, sinalize explicitamente a limitação.
Não exponha nomes, documentos, dados bancários ou qualquer informação pessoal ou sensível presente nos relatos.
Não descarte automaticamente ocorrências de baixa frequência, principalmente quando apresentarem possível impacto financeiro, operacional ou de segurança.
Evite generalizações que não possam ser sustentadas pelos registros analisados.
Utilize linguagem profissional, objetiva e compreensível tanto para profissionais de Dados quanto para áreas de Negócio.
✅ Critério de qualidade

A análise será considerada satisfatória quando conseguir transformar os feedbacks em informações estruturadas, rastreáveis e úteis para tomada de decisão, permitindo identificar problemas prioritários e orientar investigações sobre suas possíveis causas raiz.

🛠️ Ferramenta utilizada

Claude — utilizado como IA responsável pela execução dos prompts desenvolvidos durante o desafio.

🎯 Resultado esperado

O projeto demonstra como técnicas de Engenharia de Prompt podem estruturar uma análise de feedbacks bancários, estabelecendo contexto, critérios, formato de saída e restrições para reduzir respostas especulativas e gerar informações mais úteis para tomada de decisão.

📚 Tecnologias e conceitos aplicados
Inteligência Artificial Generativa
Engenharia de Prompt
Análise de Dados
Experiência do Cliente
Análise de Sentimento
Identificação de Padrões
Análise de Causa Raiz
Priorização por Criticidade
Pix e Operações Bancárias
