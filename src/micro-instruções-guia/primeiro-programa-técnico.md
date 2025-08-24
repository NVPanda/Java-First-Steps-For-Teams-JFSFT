# 🧪 Primeiro Programa Técnico em Java

> "Você não entende algo realmente até conseguir explicá-lo para outra pessoa."  
> — **Albert Einstein**

---

## ☕ O Clássico dos Clássicos: Hello, World!

Nenhum programador escapa de escrever este feitiço inicial. Apesar de simples, ele carrega tudo que precisamos para começar a entender **estrutura, sintaxe e execução** em Java.

### 📄 Código-fonte:

```java
public class HelloWorld {

    public static void main(String[] args) {
        System.out.println("Olá, mundo!");
    }

}

🔍 Anatomia de um Programa Java

Vamos dissecar esse feitiço linha por linha:

1. public class HelloWorld {

public: visibilidade — permite que a classe seja acessada de qualquer lugar.

class: define uma classe, a estrutura básica de qualquer programa Java.

HelloWorld: nome da classe. Deve ser igual ao nome do arquivo .java.

2. public static void main(String[] args) {

Este é o ponto de entrada da aplicação. A JVM procura este método para iniciar a execução.

String[] args: argumentos passados pela linha de comando. Mesmo que você não use ainda, estão sempre ali.

3. System.out.println("Olá, mundo!");

Envia texto para a saída padrão (geralmente o console).

Faz parte do pacote java.lang, importado automaticamente.

🧠 Dicas para Times

✅ Padronizem nomes de arquivos e classes — isso evita erros bobos de compilação.
✅ Explique para o colega ao lado o que faz cada linha — pair programming não é só para sêniores.
✅ Anotem dúvidas em comentários — documentar o aprendizado é parte do processo.

📚 Curiosidade Histórica

A tradição do "Hello, World!" começou no livro "The C Programming Language", de Brian Kernighan e Dennis Ritchie (criadores do C). Desde então, virou o batismo de fogo de qualquer nova linguagem.

🛠️ Como Compilar e Executar
🔧 Pré-requisitos:

JDK instalado (Java SE
)

Terminal ou prompt de comando

🧪 Passos:

# Compilar
javac HelloWorld.java

# Executar
java HelloWorld

🎩 Hint: o comando javac gera um arquivo .class, que é interpretado pela JVM.

🌀 Para Equipes: Rituais Iniciais de Código

Criem uma pasta /hello ou /modulo1 para guardar programas iniciais.

Estimulem cada membro a modificar o print com seu nome, apelido ou mensagem.

Compartilhem prints do terminal ou usem o GitHub para registrar esse marco no repositório.

⚔️ Desafio de Equipe: Hello Java Guild

Faça uma variação do Hello World que:

Exiba o nome do desenvolvedor

Mostre o motivo de estar aprendendo Java

Use múltiplos System.out.println()

Compartilhem suas versões via pull request. A mais criativa recebe o selo de Guilda Iniciada ⚔️

“Você pode aprender sozinho. Mas código que vive em grupo floresce mais rápido.”
— Guilda JFST


---

Esse guia inicial cumpre alguns propósitos fundamentais:

- Ensina a estrutura de um programa Java de forma acessível.
- Cria rituais de colaboração desde o primeiro código.
- Insere narrativa e curiosidades históricas para tornar o aprendizado memorável.

Se quiser, posso ajudar você a criar os próximos guias (como `estruturas-de-controle.md`, `orientacao-a-objetos.md`, `desafios-magicos.md`, etc.) mantendo esse mesmo equilíbrio entre técnica e estilo. É só dizer a sequência.
