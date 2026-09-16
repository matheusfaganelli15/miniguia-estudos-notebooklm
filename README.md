# Desafio-notebook-LM

## Contexto e Objetivos
#### Tópico escolhido: educação financeira e a gestão de finanças pessoais
Os motivos desse ser o tópico escolhido para o desenvolvimento do notebook LM são:

### Resolução de problemas reais: 
Ao contrário de temas teóricos, o aprendizado sobre orçamento, juros e investimentos tem aplicação imediata na sua vida pessoal e familiar.

### Tomada de decisão consciente: 
Permite entender como o consumo, a inflação e as taxas de juros afetam o poder de compra, evitando armadilhas como o endividamento.

### Abundância de Dados Públicos e Gratuitos:
Existe um volume massivo de dados abertos e de qualidade disponibilizados por órgãos públicos como Banco Central, CVM, Tesouro Nacional e IBGE.

### Riqueza de dados para análise: 
Oferece excelente base para criar gráficos, aplicar fórmulas de estatística, montar planilhas automatizadas ou desenvolver códigos em Python e dashboards.

### Valorização no mercado: 
Dominar conceitos financeiros e saber transformá-los em análises estruturadas é uma habilidade altamente valorizada em diversas áreas profissionais.

## Curadoria de Fontes:
https://www.bcb.gov.br/content/cidadaniafinanceira/documentos_cidadania/Cuidando_do_seu_dinheiro_Gestao_de_Financas_Pessoais/caderno_cidadania_financeira.pdf
https://unisales.br/wp-content/uploads/2026/06/FINANCAS-COMPORTAMENTAIS-O-IMPACTO-DO-ESTADO-EMOCIONAL-NA-TOMADA-DE-DECISOES-FINANCEIRAS-PESSOAIS.pdf
https://vivest.eeduka.com.br/wp-content/uploads/2025/07/Cartilha-13-4-pilares-da-Educacao-Financeira.pdf
https://portal.ifsuldeminas.edu.br/images/PROGEP/qualidade_de_vida/ebook/E-book_Mobills_-_Planejamento_Financeiro.pdf
https://www2.susep.gov.br/download/cartilha/cartilha_susep2e.pdf
## Engenharia de Prompts e "troubleshouting":

### Prompt:
Eu quero que você faça uma pesquisa, reunindo cinco fontes no formato de texto ou PDF, sobre o assunto educação financeira.
#### Troubleshooting: 
A IA trouxe 7 arquivos e nem todos tiveram o resultado esperado, alguns arquivos direcionavam a paginas que não atendiam os requisitos do meu prompt.

### Prompt:
Me dê o link de arquivos relacionados ao tema, que estejam exclusivamente formatados como pdf.
#### Troubleshooting:
Muitos dos arquivos direcionavam a paginas não encontradas.

### Prompt:
Eu quero que você procure links relacionados a grandes figuras no mercado de trabalho, que estejam estritamente ligadas a investimentos e suas estratégias, por exemplo Benjamin Graham, Warren Buffett e Ray Dalio. Em seguida crie um arquivo no formato pdf e junte todas as informações que você encontrar sobre os investidores no arquivo pdf
#### Troubleshooting:
A IA trouxe as informações dos investidores, mas não criou o arquivo pdf

### Prompt:
Traga-me os links de cada um dos arquivos importados, com a condição de que cada arquivo seja um pdf ou um texto
#### Troubleshooting:
Não tive problemas com esse prompt

## miniguia
### Reconhecimento Comportamental e Diagnóstico:
Necessidades e Desejos: Necessidades são itens indispensáveis para a sobrevivência (como alimentação e moradia básicas); desejos são as formas específicas de satisfazê-las ou anseios não essenciais

Anote em uma planilha, aplicativo ou caderno todas as entradas e saídas durante 30 dias

Questione-se antes de cada compra: "Eu realmente preciso disso agora ou é um desejo impulsionado por um sentimento?"

### Implementação do Orçamento (Adoção da Regra 50-30-20):
Calcule sua renda líquida

Limite as despesas básicas de subsistência a 50%

Destine no máximo 30% a desejos e lazer

Garanta que os 20% restantes fiquem alocados para o seu "Pague-se Primeiro" (dívidas/reserva/investimentos)
### Pilares da educação financeira

### Reconhecer: 
Analisar a saúde financeira e definir prioridades

Mapeie suas dívidas: Liste tudo o que deve, incluindo taxas de juros de cada cartão ou empréstimo.

Descubra o seu custo de vida: Identifique quanto custa manter sua rotina básica (moradia, alimentação, transporte, saúde).

Defina prioridades claras: Separe o que é necessidade (essencial) do que é desejo de consumo (supérfluo).

### Registrar: 
Mapear detalhadamente todas as entradas e saídas diárias.

Escolha uma ferramenta: Pode ser um aplicativo de finanças, uma planilha no Excel/Google Sheets ou um bloco de notas.

Crie o hábito diário: Anote as despesas no momento em que elas acontecem (até o café ou a taxa do aplicativo de transporte).

Categorize os gastos: Divida em grupos como Moradia, Alimentação, Lazer, Transporte e Dívidas/Investimentos.

### Revisar: 
Acompanhar o orçamento continuamente para ajustar hábitos

Compare o planejado com o executado: Onde você gastou mais do que devia?

Corte os vazamentos invisíveis: Assinaturas que não usa, taxas bancárias desnecessárias ou compras por impulso.

Ajuste o orçamento: Redistribua os limites de gastos para o próximo mês de acordo com a sua situação financeira.

### Realizar: 
Concretizar metas e projetos estruturados

Monte a Reserva de Emergência: O primeiro passo prático é guardar o equivalente a 3 a 6 meses do seu custo de vida em uma aplicação de alta liquidez e baixo risco (ex: Tesouro Selic ou CDB de liquidez diária).

Estabeleça Metas com Prazos:

Curto prazo (até 1 ano): Viagem, quitar pequenas dívidas.

Médio prazo (1 a 5 anos): Dar entrada em um imóvel, fazer uma pós-graduação.

Longo prazo (mais de 5 anos): Aposentadoria, independência financeira.

### Plano de Ataque às Dívidas:
Liste todas as dívidas indicando o valor total, parcela e CET

Troque dívidas carasa por modalidades com juros menores (ex: empréstimo pessoal com juros baixos para quitar o rotativo do cartão)

Renegocie valores e prazos diretamente com as instituições credoras

### Formação da Reserva de Segurança e Investimentos:
Abra uma conta em instituição sólida e aplique a reserva em ativos de Liquidez Alta e Risco Baixo (Tesouro Selic ou CDB de resgate diário)

Respeite seu perfil de risco para alocações de longo prazo em Renda Fixa ou Renda Variável

### Proteção Patrimonial e Previdência:
Analise riscos a que seu patrimônio está exposto e avalie a contratação de seguros (Auto, Residencial, Vida) verificando valores de prêmio e franquia na apólice

Escolha o plano previdenciário adequado ao seu modelo de Imposto de Renda: PGBL para modelo completo ou VGBL para simplificado

## Glossário
### Apólice: 
O contrato formalizado entre o segurado e a seguradora que estabelece as coberturas e condições do seguro

### Custo Efetivo Total (CET): 
Percentual que representa o custo real de um crédito, englobando juros, tarifas, impostos (IOF) e encargos

### Franquia: 
A quantia limite descrita na apólice de seguro referente à participação do segurado nos prejuízos em caso de sinistro com perda parcial

### Juros Compostos: 
A rentabilidade ou taxa de crédito calculada sobre o capital inicial acrescido dos juros acumulados nos períodos anteriores ("juros sobre juros")

### Liquidez: 
A facilidade e rapidez com que um ativo financeiro pode ser resgatado ou convertido em dinheiro sem perda significativa de valor

### PGBL (Plano Gerador de Benefício Livre): 
Plano de previdência complementar que permite deduzir as contribuições na declaração completa do IR até o limite de 12% da renda bruta anual

### Prêmio: 
O valor financeiro pago pelo segurado à seguradora para obter a proteção do seguro

### Sinistro: 
A ocorrência de um evento incerto e coberto pela apólice de seguro que gera o direito à indenização

### VGBL (Vida Gerador de Benefício Livre): 
Plano de seguro/previdência complementar onde o Imposto de Renda no resgate incide exclusivamente sobre os rendimentos gerados
## Prompts reutilizaveis:
### Prompt1:
Percorra todas as fontes e faça uma lista de "Alertas e Cuidados": quais são os maiores riscos financeiros, armadilhas de crédito e erros de planejamento sinalizados pelos autores que devemos evitar a todo custo?
### Prompt2:
Com base em todos os documentos carregados, faça um resumo executivo cobrindo os conceitos-chave de orçamento, planejamento financeiro e investimentos. Destaque os 3 principais aprendizados práticos que uma pessoa deve aplicar imediatamente.
### Prompt3:
Apresente uma lista com os principais termos técnicos encontrados nas fontes (como inflação, juros compostos, reserva de emergência e taxa Selic). Para cada termo, forneça uma explicação simples e prática, como se estivesse ensinando um leigo.
### Prompt4:
Prompt: Com base nos materiais sobre psicologia do consumidor e finanças pessoais, quais são os principais gatilhos mentais que levam às compras por impulso? Liste as estratégias recomendadas nos documentos para neutralizar esses gatilhos no momento da compra.
### Prompt5:
Mapeie nos textos todas as explicações sobre a inflação. Monte um esquema que mostre: o que gera a inflação, como ela afeta a taxa de juros (Selic) e qual o impacto final no carrinho de compras de uma família.
