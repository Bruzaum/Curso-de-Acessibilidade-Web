# Curso-de-Acessibilidade-Web
Curso feito na Alura. Link: https://cursos.alura.com.br/course/acessibilidade-web-front-end

O código foi originalmente feito pelo professor do curso. Fiz algumas alterações vistas nas aulas.

Anotações feitas:
  -Organizar os itens por h1, h2, ... que faça sentido para quem está escutando: "Cabeçalho nível 1" ou "Cabeçalho nível 2";
  
  -Deixar o lang correto no site todo. Se tiver algo que preciser ser lido em inglês, por exemplo, só alterar para aquela linha o lang="en" ;
  
  -Colocar alt nas imagens e não inserir "Foto de" ou "Imagem de", etc. O leitor já dirá que é uma foto;
  
  -Quando usado um svg, nao temos o alt, entao utilizamos o <title></title>, porém o leitor le o title + desc;
  
  -alt tem que fazer sentido para o contexto, se uma imagem for somente visual, pode deixar um alt vazio para não atrapalhar o leitor;
  
  -o leitor fala "Bolinha 20 manutenções mensais" ou "Um ponto 20 manutenções mensais". Em resumo, o CSS pode atrapalhar a acessibilidade, assim podemos repensar no melhor método para deixar o visual bonito e inclusivo;
  
  -Tomar cuidado com display:none e visibility: hidden, pois o leitor não lê ele. Um jeito de contornar é jogar o elemento para o "infinito" à esquerda, ex: left -9999px;
  
  -Interessante ter um jeito de pular os itens de navegação, para facilitar a navegação pelo teclado. Podemos fazer isso com CSS;
  
  -Adicionar role para facilitar. Exemplo na main, adicionar role= "main". Todas as roles: https://www.w3.org/TR/using-aria/#intro;
  
  -Principal função do atributo role é mudar a semântica de um elemento;
  
  -Trocar o disabled para readonly;
