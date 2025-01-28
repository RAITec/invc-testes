# invc-testes

## Fluxo >Normal< de trabalho nos repositórios da Inovação

### 1. Vire colaborador do repositório de interesse
- Peça para a coordenação te adicionar como colaborador no repositório do GitHub.
- Informe seu username do GitHub.
- Após isso, você receberá um convite na sua conta do GitHub. Acesse sua conta e aceite o convite para ganhar permissão de colaboração.

---

### 2. Clone o repositório
- Primeiro, copie o link do repositório para o qual você foi adicionado. O link geralmente fica disponível na página inicial do repositório no GitHub.
  
- Abra o terminal na pasta onde você deseja armazenar o repositório clonado.

- Execute o seguinte comando no terminal para clonar o repositório:

```bash
    git clone <link-do-repositório>
```

Isso cria uma cópia do repositório no seu computador, permitindo que você faça modificações localmente.

---

### 3. Caso você já tenha o projeto no seu computador
- Se você já clonou o repositório anteriormente, mas quer atualizar seu projeto local com as últimas mudanças feitas por outros colaboradores, você pode usar o comando `git pull` para baixar as atualizações.

- No terminal, estando na pasta do repositório, execute:

```bash
    git pull
```

Esse comando vai fazer o download das últimas alterações feitas no repositório remoto e atualizar sua cópia local.

---

### 4. Faça as alterações no código
- Agora, você pode começar a editar os arquivos conforme necessário para implementar novas funcionalidades ou corrigir bugs.
  
- Quando você terminar de fazer as alterações desejadas, adicione as modificações ao "stage" (preparando-as para o commit) com o comando:

```bash
    git add .
```

- Em seguida, faça o commit das alterações. O commit deve ter uma mensagem clara e concisa, descrevendo o que foi alterado no código. Evite mensagens vagas como "atualizações" ou "correções".

```bash
    git commit -m "Descrição das alterações"
```

Quando for escrever a mensagem de commit, pense na pergunta "O que a minha alteração faz?". A mensagem deve responder a essa questão de forma objetiva. Por exemplo: "Corrige variáveis de controle no cálculo de X"


---

### 5. Envie as alterações para o GitHub
- Neste momento, as alterações feitas ainda estão apenas no seu computador. Para que as mudanças fiquem visíveis no repositório remoto do GitHub, você deve fazer o "push" das suas alterações.

- Para enviar a branch padrão (geralmente `main` ou `master`), basta:

```bash
    git push
```

- O comando `git push` envia suas alterações para o repositório remoto no GitHub, tornando-as visíveis para todos os colaboradores do projeto.

### 6. Em caso de projetos grandes

Nesse caso, capacite-se com técnicas mais robustas de versionamento para que o código não se transforme em uma bagunça!

Aqui está um excelente material de estudo: https://www.youtube.com/watch?v=S7XpTAnSDL4&ab_channel=JavaScriptMastery

obs: não precisa instalar a IDE do vídeo, qualquer terminal serve.

---

## Faça o teste!

Para entender o fluxo de trabalho do Git, recomendo que você siga estas etapas e pratique os comandos. Isso vai te ajudar a se familiarizar com o processo. Crie um arquivo Python com o nome `seu-nome.py` e escreva o programa inspirado numa das ideias na lista abaixo. Você pode até usar o ChatGPT pra fazer o código, o importante é que você entenda o processo de usar o Git para versionar e compartilhar seu trabalho.

#### Conversor de texto para código Morse
Crie um programa que converta uma string de texto para código Morse e vice-versa.

#### Conversor de temperatura
Um programa que converta temperaturas entre Celsius, Fahrenheit e Kelvin.

#### Gerador de senhas
Crie um programa que gere senhas aleatórias com letras, números e caracteres especiais.

#### Contador de palavras
Solicite ao usuário que insira uma frase e conte o número de palavras e caracteres.

#### Tabuada automática
Gere e exiba a tabuada de um número escolhido pelo usuário.

#### Calculadora básica
Crie um programa que some, subtraia, multiplique e divida dois números inseridos pelo usuário.

#### Jogo da adivinhação
Gere um número aleatório e peça ao usuário para adivinhar até acertar, com dicas se o palpite está alto ou baixo.

#### Calculadora de IMC (Índice de Massa Corporal)
Receba o peso e a altura do usuário, calcule o IMC e classifique-o como "Abaixo do peso", "Normal", "Sobrepeso" ou "Obeso".

#### Simulador de dados 
Simule o lançamento de um dado (ou vários dados) e exiba os resultados.

#### Cadastro simples de contatos
Permita ao usuário adicionar, visualizar e excluir contatos em uma lista (apenas nome e telefone, por exemplo).
