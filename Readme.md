# Como passar um objeto  como parametro da função:
1 Passo: A gente pega o "pessoa" que instanciou e chama a  função,
* var pessoa = new Pessoa();
* var filho = new Filho();  

Em seguida passa o parametro no caso (filho)  "returnFilho(filho)"  e retorna a ele mesmo. Sendo assim chama-se este metodo teremos acesso ao proprio Objeto (filho).
*  alert( pessoa.returnFilho(filho).nome);# Danki_Code-Fun-o-Instancia-Objeeto
