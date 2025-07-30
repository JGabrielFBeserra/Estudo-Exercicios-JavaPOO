# 🧪 Estudo - Exercícios em Java

Este projeto contém uma atividade prática de Java que utiliza conceitos como classes abstratas, exceções personalizadas, herança e manipulação de arquivos.

## 📚 Enunciado

1. **Crie a classe abstrata `Conta` com:**
   - Atributos:
     - `numero` (int)
     - `titular` (String)
     - `saldo` (double)
   - Método abstrato:
     - `void sacar(double valor)` lança `SaldoInsuficienteException`
   - Métodos concretos:
     - `void depositar(double valor)`
     - `void imprimirDados()` para exibir as informações da conta

2. **Crie a exceção personalizada `SaldoInsuficienteException`**

3. **Crie a subclasse `ContaCorrente`**
   - Implemente o método `sacar`, lançando a exceção em caso de saldo insuficiente

4. **No método `main`:**
   - Leia os dados de uma conta a partir do arquivo `conta.txt`  
     *(formato: número, titular, saldo — em uma única linha separados por vírgula)*
   - Crie um objeto `ContaCorrente` com os dados lidos
   - Solicite ao usuário um valor para saque
   - Tente realizar o saque:
     - Trate a exceção adequadamente
     - Exiba mensagens apropriadas ao usuário
   - Grave os dados atualizados no arquivo `conta_atualizada.txt`

---

## ✅ Conceitos abordados

- ✅ Classes abstratas  
- ✅ Exceções personalizadas  
- ✅ Herança  
- ✅ Manipulação de arquivos em Java  
- ✅ Entrada e saída via terminal  

---

## 📁 Estrutura esperada dos arquivos

- `Conta.java` (classe abstrata)
- `ContaCorrente.java` (subclasse concreta)
- `SaldoInsuficienteException.java` (exceção personalizada)
- `Main.java` (programa principal)
- `conta.txt` (arquivo de entrada)
- `conta_atualizada.txt` (arquivo de saída)

---

## 🧠 Requisitos

- Java 8 ou superior
- IDE como NetBeans, IntelliJ ou Eclipse (opcional)
- Terminal/Console
