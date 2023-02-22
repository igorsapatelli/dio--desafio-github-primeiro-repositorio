# Programação Orientada a Objeto

## Definição

Paradigma de análise, projeto e programação de sistemas de software baseada na composição e interação entre diversas unidades de software chamadas de objetos.



## Fundamentos

* Abstração
  * "Processo pelo qual se isolam características de um objeto, considerando os que tenham em comum certos grupos de objetos."
* Encapsulamento
  * "Capacidade de esconder complexidade e proteger dados.
* Reuso
  * "Capacidade de criar novas unidades de código a partir de outras já existentes."



# Classes, Métodos, Atributos e Objetos



# Criando Entidades

**Objetivos**

* Apresentar os conceitos que ajudam a criar entidades a partir de outras entidades:
  * Herança
  * Associação
  * Interface
* 

## Herança

"É o relacionamento entre classes em que uma classe chamada de subclasse(classe filha, classe derivada) é uma extensão, um subtipo, de outra classe chamada de superclasse (classe pai, classe mãe, classe base). Devido a isto, a subclasse consegue reaproveitar os atributos e métodos dela. Além dos que venham a ser herdados,a subclasse pode definir seus próprios membros."

Exemplo:

**JAVA**

`**class** A ***extends*** B {`

`}`

### Tipos de herança

* Simples

  * A classe filha tem só uma classe mãe:

    **Funcionário** :arrow_left: vendedor

    ​						:arrow_left: gerente

    ​						:arrow_left: faxineiro

    

* Múltipla

  * A classe filha tem uma ou mais classes mães

    **Estudante** :arrow_left: estagiario :arrow_right: **Funcionario**

    obs: estagiário herda de Estudantes e Funcionário

    Java não possui herança múltipla.



## Polimorfismo

"A mesma ação se comportando diferente"



## Sobrescrita

"A mesma ação, podendo se comportar diferente"



## Associação

* Tipos
  * Estrutural
    * Composição
    * Agregação
  * Comportamental
    * Dependência
* **Estrutural**
  * Composição: "Com Parte Todo"
  * Ex: Pessoa e Endereço



* Agregação : "Sem Parte Todo"
  * Disciplina e Aluno

