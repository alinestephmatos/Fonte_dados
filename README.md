# Fonte_dados
## Matéria Fatec 2025-2 - Atividade: Aprendendo a utilizar o Github
<img width="1654" height="765" alt="image" src="https://github.com/user-attachments/assets/d7178eac-9723-42ba-8a2d-c080100d4d03" />

##Atividade: Apresentação do trabalho - 1º Semestre
Apresentação de trabalho em grupo, falando sobre o perfil de cada integrante, vida social e trabalho.

##Atividade em sala: 
Acessar https://repositorio.seade.gov.br/dataset/seade-industria e obter um arquivo mais atualizado, no formato CSV ou XLSX ou XLS
Gerar tabela e gráfico dinâmico para visualização dos dados
Usando fórmulas responder às perguntas a seguir:  a) quantos municípios foram contemplados nos dados? (REMOVER DUPLICATAS - CONT.VALORES)  b) quantas cadeias produtivas foram consideradas nos dados? (REMOVER DUPLICATAS - CONT.VALORES) c) considerando o ano de 2020, qual foi o maior valor  gerado em VTI-(MilReais) para São José dos Campos?(MÁXIMOSES)   d) qual foi a cadeia produtiva que forneceu o  resultado anterior para São José dos Campos? (ÍNDICE  e CORRESP)
Elaborar mais 5 perguntas que os dados, presentes no arquivo obtido, possam responder.
Gerar  fórmulas para responder às perguntas do item anterior
Grave e poste o arquivo gerado em seu Github, editando o README de forma a explicar cada fórmula utilizada.

### Atividade: Planilha de municípios com fórmulas
 1) QUANTIDADE MUNICIPIOS: 645,00 
fórmula utilizada para contagem de municípios "=CONT.VALORES(A:A)-1"

 2) QUANTIDADE DE CADEIAS PRODUTIVAS: 24,00 
fórmula utilizada para contagem de cadeias produtivas "=CONT.VALORES(C:C)-1"

 3) MAIOR VALOR GERADO EM 2020, EM SJC (VTI-MIL REAIS): 9.681.743,86 
fórmula utilizada para contagem do valor gerado "=MÁXIMOSES(sp_municipal!G:G;sp_municipal!D:D;2020;sp_municipal!B:B;"São José dos Campos")"

 4) MAIOR VTI EM 2007: 11.721.509,53 
fórmula utilizada para achar o maior valor de VTI "=MÁXIMOSES(sp_municipal!G:G;sp_municipal!D:D;2007)"

 5) CADEIA PRODUTIVA, CUJO O VTI FOI MAIOR EM 2007	 Produtos Derivados Do Petróleo 
fórmula utilizada para encontrar a cadeia produtiva "=ÍNDICE(sp_municipal!F:F;CORRESP(G18;sp_municipal!G:G;0);1)"

### Atividade: Criação de dashboard
1) Pesquisa de dados no Comex de exportações em 2025 nos municípios
2) Criação de dashboard com os dados de exportações nos municípios em 2025.
