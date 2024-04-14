# Como passar um objeto  como parametro da função:
1 Passo: Criar  o objeto "pessoa" que instanciou e chama a  função,

     var pessoa = new Pessoa();
     var filho = new Filho();
 

Em seguida passa o parametro no caso (filho)  "returnFilho(filho)"  e retorna a ele mesmo. Sendo assim chama-se de método. Teremos acesso ao proprio Objeto (filho).

    this.returnFilho = function(filho){
        return filho;
    }
    
    alert(pessoa.returnFilho(filho).nome);
# Classes:
## Método constructor, toda vez  que instancia e instanciar é criar um objeto e em seguida passar um parametro no caso (nome).
 
 
    constructor(nome){
    
        this.nome = nome;
}

# Criando uma função
 Apesar de ser uma função e orientação a objeto é chamado  de metódo.
    
    printNome(){
        return this.nome;

                }
# O que é extends:
É você declarar tudo que esta no classe  (Filho) e herda tudo que tem na classe (Pessoa).
    
        class Filho extends Pessoa{ 
            constructor(nome){
                    super(nome);
                    this.idade = "12 anos";
            }
        }