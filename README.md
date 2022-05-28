# POO-Boundary-Control-e-Entity

## Exercício - Museu (Boundary, Control e Entity) – Simplificado Usando Java FX

- Crie um CRUD para fazer a manutenção de visitantes do museu, contendo o Boundary, o Control e a Entidade (BCE), vinculando os componentes gráficos do tipo TextField com as propriedades do aluno, contendo um botão para adicionar novo aluno e outro para pesquisar, conforme layout em anexo¹:

- Crie a classe da Entidade com os atributos todos como privado 
  - Visitante:
  - id        
  - nomeVisitante
  - nomeEscola
  - dataVisita (pode ser tipo Date ou LocalDate)

- Crie a classe Boundary conforme o diagrama de classe em anexo:
  - Declare os componentes gráficos necessários conforme o layout em anexo, como sendo variáveis de instância, lembre-se que você não precisa declarar os componentes do tipo Label, desde que os crie diretamente quando forem ser adicionados no GridPane
  - Escreva o código do método start() para que ele crie um objeto do tipo GridPane e posicione os componentes gráficos conforme o layout em anexo
  - Faça a classe Boundary implementar a interface EventHandle<ActiveEvent> e sobreescreva o método handle para acionar o método adicionar() do Control quando o botão adicionar for pressionado, e para acionar o método pesquisar() do Control quando o botão pesquisar for pressionado

- Crie a classe Control escrevendo os métodos conforme abaixo:
  - void adicionar(Visitante v), deverá colocar o objeto do tipo Entidade recebido como parâmetro dentro do array
  - Visitante pesquisar(), deverá procurar no array pelo nome passado como parâmetro
  
¹![Boundary sem tabela](https://user-images.githubusercontent.com/54561697/170828738-1127ae74-d9b9-43f2-b37d-a38160700b88.png)

²![diagrama de classe simples sem tabelas nem banco](https://user-images.githubusercontent.com/54561697/170828743-b80e87b8-5d3b-4254-bd18-9e0a858eacd0.png)
