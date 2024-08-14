# CRUD PYTHON COM PKL
🎈GERENCIE O NOME, IDADE, EMAIL E TELEFONE DOS USUÁRIOS EM UM ARQUIVO PKL.

<img src="FOTO.png" align="center" width="500"> <br>

## DESCRIÇÃO:
O aplicativo é um sistema básico de gerenciamento de usuários implementado em Python, utilizando um paradigma de CRUD (Create, Read, Update, Delete) para realizar operações simples em um arquivo de texto.

## RECURSOS:
1. **Adicionar Usuário:**
   - Permite a adição de um novo usuário ao sistema.
   - Solicita o nome, idade, email e telefone do usuário por meio da entrada do usuário.
   - Qualquer um dos campos (idade, email e telefone) pode ser deixado em branco ao pressionar Enter.
   - Os dados do usuário são armazenados em um arquivo de texto chamado `"usuarios.pkl"` no mesmo diretório do código.

2. **Listar Usuários:**
   - Exibe uma lista de todos os usuários cadastrados no sistema.
   - Recupera as informações do arquivo `"usuarios.pkl"` e apresenta o nome, idade, email e telefone de cada usuário.

3. **Atualizar Usuário:**
   - Permite a atualização das informações de um usuário existente.
   - Solicita o nome do usuário a ser atualizado e os novos dados (nome, idade, email e telefone).
   - Qualquer um dos campos (idade, email e telefone) pode ser deixado em branco ao pressionar Enter, mantendo o valor anterior.
   - Atualiza o arquivo `"usuarios.pkl"` com as informações atualizadas.

4. **Excluir Usuário:**
   - Possibilita a exclusão de um usuário do sistema.
   - Solicita o nome do usuário a ser excluído e remove suas informações do arquivo `"usuarios.pkl"`.

5. **Persistência de Dados:**
   - Utiliza manipulação de arquivos para armazenar as informações dos usuários de forma persistente.
   - O arquivo `"usuarios.pkl"` é criado automaticamente se não existir no mesmo diretório do código.

6. **Interface de Texto Simples:**
   - A interação com o aplicativo é realizada por meio de um menu de texto simples, apresentando opções numeradas.
   - O usuário escolhe a operação desejada digitando o número correspondente.

7. **Encerramento Controlado:**
   - Permite ao usuário sair do aplicativo de maneira controlada, encerrando o programa de acordo com sua escolha.

## EXECUTANDO O PROJETO:
1. **Instalação das Dependências::**
   - Entre no diretório `CODIGO` e execute o comando:

   ```bash
   pip install -r requirements.txt
   ```

2. Para executar o arquivo Python, utilize o comando abaixo no terminal, dentro do diretório `./CODIGO`:

   ```
   python CODIGO.py
   ```

3. Isso iniciará o aplicativo e exibirá um menu com as seguintes opções:
   - **1. ADICIONAR USUÁRIO:** Permite adicionar um novo usuário ao sistema. Você será solicitado a digitar o nome, idade, email e telefone do usuário. Qualquer um dos campos (idade, email e telefone) pode ser deixado em branco ao pressionar Enter.
   - **2. LISTAR USUÁRIOS:** Exibe uma lista de todos os usuários cadastrados, mostrando seus nomes, idades, emails e telefones.
   - **3. ATUALIZAR USUÁRIO:** Permite atualizar as informações de um usuário existente. Você será solicitado a digitar o nome do usuário que deseja atualizar, o novo nome, a nova idade, o novo email e o novo telefone. Qualquer um dos campos (idade, email e telefone) pode ser deixado em branco ao pressionar Enter, mantendo o valor anterior.
   - **4. EXCLUIR USUÁRIO:** Permite excluir um usuário existente. Você será solicitado a digitar o nome do usuário que deseja excluir.
   - **5. SAIR:** Encerra o aplicativo.
4. Escolha a opção desejada digitando o número correspondente e pressionando Enter.
5. Siga as instruções apresentadas na tela para realizar as operações desejadas, como adicionar, listar, atualizar ou excluir usuários.
6. Após concluir uma operação, o menu será exibido novamente para que você possa escolher outra opção, ou você pode optar por sair do aplicativo digitando "5" e pressionando Enter.

## NÃO SABE?
- Entendemos que para manipular arquivos em muitas linguagens, é necessário possuir conhecimento nessas áreas. Para auxiliar nesse aprendizado, oferecemos cursos gratuitos disponíveis:
* [CURSO DE PYTHON](https://github.com/VILHALVA/CURSO-DE-PYTHON)
* [CONFIRA MAIS CURSOS](https://github.com/VILHALVA?tab=repositories&q=+topic:CURSO)

## CREDITOS:
- [PROJETO BASEADO NO "CRUD PYTHON EM PKL"](https://github.com/VILHALVA/CRUD-PYTHON-EM-PKL)
- [PROJETO FEITO PELO VILHALVA](https://github.com/VILHALVA)


