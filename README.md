# Password Vault (Cofre de Senhas)

Este é um projeto em **Java** desenvolvido para o gerenciamento seguro (ou armazenamento) de senhas, utilizando uma interface via terminal.

## Estrutura do Projeto

O projeto está organizado da seguinte forma:

*   **src/** (Diretório com o código fonte)
    *   `Main.java` - Ponto de entrada do aplicativo (método `main`).
    *   `Menu.java` - Gerencia o menu interativo e as opções do usuário no terminal.
    *   `Password_Master.java` - Responsável pela lógica da senha mestre (autenticação de acesso ao cofre).
*   `.gitignore` - Arquivo para evitar o envio de arquivos desnecessários (como as configurações da IDE) para o Git.
*   `README.md` - Documentação do projeto.

## Tecnologias Utilizadas

*   **Java 21**

## Como Executar o Projeto

### Pré-requisitos
Você precisa ter o Java JDK instalado na sua máquina (versão 11 ou superior recomendada, e a chave mestra é 123).

### Passo a Passo

1. **Clonar o repositório:**
   ```bash
   git clone https://github.com
   ```

2. **Navegar até a pasta do projeto:**
   ```bash
   cd Password_Vault_First
   ```

3. **Compilar e Executar:**
   Abra a pasta do projeto na sua IDE de preferência (como o IntelliJ IDEA) e execute o arquivo `Main.java`.
