Nome: Felipe Coimbra Rocha dos Santos

# Orientação a Objetos
Em Programação Orientada a Objetos, os problemas são pensados em termos de OBJETOS, propriedades e métodos.

### Exemplo
* Biblioteca - Para esse sistema, teremos uma divisão de objetos, tais como Livro, Andar, Matéria, Atendente, Usuário.

# Classe 
Uma classe representa o conjunto de objetos que possuem determinadas características em comum. Ao definirmos uma classe, temos que definir dois pontos principais:
* Atributos - Informações da classe. Ex: cor do cabelo, sexo, altura...
* Métodos - Ações que podem ser realizadas pelos objetos de cada classe. Ex: andar, correr, pular, falar...

### Exemplo
Classe Pessoa

* `Nome` - Felipe
* `Sexo` - Masculino
* `Cor do cabelo` - Preto
* `Cor dos sapatos` - Branco
* `Altura` - 1,78m
* `Humor` - Concentrado

Felipe é uma instância da classe Pessoa.

## Como criar?

```java
public class Pessoa {
    private String nome;
    private int idade;
    private char sexo;
    private double altura;
}
```

Para instanciarmos objetos, fazemos assim:
```java
new Pessoa("Felipe")
```

## Métodos de Acesso


### Exemplos GET

```java
public String getNome() {
    return nome
}
```

### Exemplos SET

```java
public void setNome(String nome) {
    this.nome = nome;
}
```