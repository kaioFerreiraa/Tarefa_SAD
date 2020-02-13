# Tarefa_SAD
Fazer um README.MD sobre a ferramenta BI utilizada

# Markdown

para fazer a tarefa do Datawarehouse, primeiro tem que ser feito o download das ferramentas que serão usadas, no meu caso eu escolhi o pgadmin4 e o power BI.

primeiro o passo a passo da instalação do pgadmin 4 no windows 10:
![alt text](https://github.com/kaioFerreiraa/Tarefa_SAD/blob/master/imagens/WhatsApp%20Image%202020-02-13%20at%2013.56.18.jpeg)

![alt text](https://github.com/kaioFerreiraa/Tarefa_SAD/blob/master/imagens/WhatsApp%20Image%202020-02-13%20at%2013.56.19.jpeg)

![alt text](https://github.com/kaioFerreiraa/Tarefa_SAD/blob/master/imagens/WhatsApp%20Image%202020-02-13%20at%2013.56.19%20(1).jpeg)

![alt text](https://github.com/kaioFerreiraa/Tarefa_SAD/blob/master/imagens/WhatsApp%20Image%202020-02-13%20at%2013.56.19%20(3).jpeg)

![alt text](https://github.com/kaioFerreiraa/Tarefa_SAD/blob/master/imagens/WhatsApp%20Image%202020-02-13%20at%2013.56.20.jpeg)

Depois foi a instalação do power BI pelo microsoft store, no caso do power bi, ele só está apto para windows.
![alt text](https://github.com/kaioFerreiraa/Tarefa_SAD/blob/master/imagens/Capturar.PNG)

Após a instalação das duas ferramentas, se inicia a ideia do datawarehouse, criando as tabelas, primerio cada uma das dimensões que compõe o cubo do fato. A ideia aqui é fazer o fato de uma turma especial, iniciaremos com a dimensao aluno:

![alt text](https://github.com/kaioFerreiraa/Tarefa_SAD/blob/master/imagens/dimensao_aluno.PNG)

logo em seguida a do semestre:

![alt text](https://github.com/kaioFerreiraa/Tarefa_SAD/blob/master/imagens/dimensao_semestre.PNG)

logo após a dimensão horario:

![alt text](https://github.com/kaioFerreiraa/Tarefa_SAD/blob/master/imagens/dimensao_horario.PNG)

a ultima dimensão a da disciplina:

![alt text](https://github.com/kaioFerreiraa/Tarefa_SAD/blob/master/imagens/dimensao_disciplina.PNG)

Após todas as dimensões, será craido a do tabela do fato:

![alt text](https://github.com/kaioFerreiraa/Tarefa_SAD/blob/master/imagens/fato.PNG)

terminado o molde do cubo. Agora vamos ver como ele ficou no power bi, primeiro abriremos a ferramenta:

![alt text](https://github.com/kaioFerreiraa/Tarefa_SAD/blob/master/imagens/abrindo_power.PNG)

agora precisamos obter os dados com a base nas tabelas criadas no pgadmin:

![alt text](https://github.com/kaioFerreiraa/Tarefa_SAD/blob/master/imagens/obter_dados.PNG)

é necessário definir de onde está vindo seus dados, para isso pesquise o postgres:

![alt text](https://github.com/kaioFerreiraa/Tarefa_SAD/blob/master/imagens/pesquisando_postgres.PNG)

conecte seu servidor e nome do banco que foi criado:

![alt text](https://github.com/kaioFerreiraa/Tarefa_SAD/blob/master/imagens/conectando.PNG)

o power BI irá carregar os dados: 

![alt text](https://github.com/kaioFerreiraa/Tarefa_SAD/blob/master/imagens/carregando.PNG)

após o carregamento, selecione as tabelas que foram criadas:

![alt text](https://github.com/kaioFerreiraa/Tarefa_SAD/blob/master/imagens/selecionando.PNG)

e está pronto seu cubo e você pode visualiza-lo abaixo, assim como as tabelas:

![alt text](https://github.com/kaioFerreiraa/Tarefa_SAD/blob/master/imagens/estrela.PNG)

![alt text](https://github.com/kaioFerreiraa/Tarefa_SAD/blob/master/imagens/tabelas.PNG)

com todos os passos feito, todos os dados colocados no banco de dados, automaticamente já iram para o power bi.
