# 🏗️ Estrutura de uma Classe Java

> “Tudo em Java gira em torno da classe. Ela é o palco, os atores e a peça.”  
> — Guilda JFST

---

## 🔍 O Que é uma Classe?

Uma **classe** em Java é como um **molde** para criar objetos. Ela define quais dados (atributos) e comportamentos (métodos) os objetos terão.

Pense em uma classe como a *ficha técnica* de um personagem: nome, poderes, habilidades — mas o personagem só existe mesmo quando é instanciado.

---

## 🧪 Exemplo Prático: Classe `Livro`

```java
public class Livro {
    // Atributos (variáveis de instância)
    String titulo;
    String autor;
    int anoPublicacao;

    // Construtor
    public Livro(String titulo, String autor, int anoPublicacao) {
        this.titulo = titulo;
        this.autor = autor;
        this.anoPublicacao = anoPublicacao;
    }

    // Método
    public void mostrarDetalhes() {
        System.out.println("Título: " + titulo);
        System.out.println("Autor: " + autor);
        System.out.println("Ano: " + anoPublicacao);
    }
}

🔬 Anatomia da Classe
🔸 public class Livro { ... }

public: a classe pode ser acessada de qualquer lugar.

Livro: nome da classe — por convenção, inicial maiúscula e camelCase.

🔸 Atributos (ou campos)

String titulo;
String autor;
int anoPublicacao;

Definem o estado do objeto.

São variáveis que pertencem a cada instância.

🔸 Construtor

public Livro(String titulo, String autor, int anoPublicacao) { ... }

Método especial chamado automaticamente na criação do objeto.

Mesmo nome da classe.

Serve para inicializar os atributos.

🔸 Método

public void mostrarDetalhes() { ... }

Define um comportamento do objeto.

Pode acessar os atributos diretamente.

void indica que não retorna valor.

🛠️ Como Usar a Classe no main

public class Main {
    public static void main(String[] args) {
        Livro livro1 = new Livro("1984", "George Orwell", 1949);
        livro1.mostrarDetalhes();
    }
}

🧠 Hints e Boas Práticas

✅ Comece simples: uma classe, alguns atributos, um método.
✅ Use nomes descritivos e coerentes.
✅ O construtor não precisa fazer tudo — delegue lógica para métodos.
✅ Use this. para deixar claro que está se referindo ao atributo da instância.
✅ Deixe comentários explicativos no início.

🔒 Encapsulamento — Um Teaser

Por enquanto, estamos usando atributos públicos. Em breve, usaremos private + métodos get e set para proteger os dados da classe.

private String titulo;

public String getTitulo() {
    return titulo;
}

public void setTitulo(String titulo) {
    this.titulo = titulo;
}

⚔️ Desafio da Guilda

Crie uma classe chamada PersonagemRPG com os seguintes atributos:

nome (String)

classe (String)

nivel (int)

Implemente:

Um construtor

Um método exibirStatus() que imprima tudo no console

Instancie pelo menos 2 objetos diferentes no main() e invoque seus métodos.

“Em Java, objetos são entidades vivas — eles sabem coisas e fazem coisas.”
— Guilda JFST

---
