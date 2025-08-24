# 🔀 Controle de Fluxo em Java

> “O código é a arte de decidir: cada if, cada loop, molda o destino da aplicação.”  
> — Guilda JFST

---

## 🔎 Introdução

Controle de fluxo é a habilidade de direcionar a execução do programa com base em condições e repetições. Com ele, podemos fazer escolhas e repetir tarefas, fundamentais para qualquer sistema real.

---

## ⚔️ Estruturas Condicionais

### 1. `if` e `else`

```java
int idade = 18;

if (idade >= 18) {
    System.out.println("Você é maior de idade.");
} else {
    System.out.println("Você é menor de idade.");
}

O bloco if executa o código se a condição for verdadeira.

O else executa quando a condição do if é falsa.

2. else if

Para múltiplas condições:

int nota = 75;

if (nota >= 90) {
    System.out.println("Aprovado com louvor!");
} else if (nota >= 70) {
    System.out.println("Aprovado.");
} else {
    System.out.println("Reprovado.");
}

3. switch

Quando temos várias opções fixas, switch é elegante:

char letra = 'B';

switch (letra) {
    case 'A':
        System.out.println("Excelente!");
        break;
    case 'B':
        System.out.println("Bom trabalho!");
        break;
    case 'C':
        System.out.println("Pode melhorar.");
        break;
    default:
        System.out.println("Nota inválida.");
}

🔄 Estruturas de Repetição (Loops)
1. for

Ideal para repetições contadas:

for (int i = 0; i < 5; i++) {
    System.out.println("Iteração: " + i);
}

2. while

Repete enquanto a condição for verdadeira:

int contador = 0;

while (contador < 5) {
    System.out.println("Contador: " + contador);
    contador++;
}

3. do-while

Executa o bloco pelo menos uma vez:

int num = 0;

do {
    System.out.println("Número: " + num);
    num++;
} while (num < 5);

🧠 Dicas para o Time

Prefira switch quando tiver múltiplos valores fixos, melhora a legibilidade.

Use comentários para explicar decisões complexas em condições.

Evite loops infinitos! Sempre atualize a variável de controle.

Explore a ideia de "early return" para simplificar condições.

⚔️ Desafio da Guilda: Controlando Fluxos

Crie um programa que pergunte ao usuário a idade e imprima a categoria da pessoa (Criança, Adolescente, Adulto, Idoso).

Use if-else para decidir a categoria.

Faça um loop que permita que o usuário faça várias consultas até digitar “sair”.

Utilize switch para mostrar uma mensagem especial para cada categoria.

“Fluxo é a correnteza que guia o rio do código.”
— Guilda JFST

