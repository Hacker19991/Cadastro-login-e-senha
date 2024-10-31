# **AppLoginSenha (Cadastro com login e senha)**

> Um aplicativo Android desenvolvido para cadastrar e logar seus dados que serão salvos.

## Descrição
O **AppLoginSenha** permite ao usuário poder cadastra seus dados que serão salvos por uma DataBase simples criada a partir dos codigos e que mais tarde o usuário podera cadastrar seus dados para poder ser verificado e identificado corretamente.

## Funcionalidades
- [x] Entrada de dados de consumo
- [x] Cálculo e exibição de estatísticas de consumo
- [x] Gráficos interativos para visualização dos dados
- [x] Interface intuitiva e amigável
- [ ] Suporte para diferentes tipos de recursos (planejado para futuras versões)

## Tecnologias Utilizadas
- [x] **Android Studio** (versão recomendada: Bumblebee | 2021.1.1)
- [x] **Java** para desenvolvimento
- [x] **ConstraintLayout** para interface responsiva
- [x] **TextView**, **EditText** para entrada e exibição de dados

## Como Rodar o Projeto
Siga os passos abaixo para rodar o projeto localmente:

1. Clone este repositório:
   ```bash
   https://github.com/Hacker19991/Cadastro-login-e-senha
   
2. Abra o projeto no Android Studio.
   
3. Compile e execute o projeto em um emulador ou dispositivo físico.

## Estrutura do Projeto

```
── app
   ├── src
   │   ├── main
   │   │   ├── java/com/example/appconsumo
   │   │   │   ├── MainActivity.java # Onde o executaveis da Layout principal irão funcionar de maneira programada
   │   │   │   ├── DBHelper # Onde a DataBase ira amarzenar os dados do usuário e salvos para caso o usuário queira entrar de novo 
   │   │   │   ├── LoginActivity.java # Atividade onde o usuário podera logar seus dados salvos e entrar com sucesso
   │   │   │   ├── RegistrarActivity.java # Atividade onde o usuário podera cadastrar e salvar seus dados no DataBase
   │   │   ├── res
   │   │   │   ├── layout
   │   │   │   │   ├── activity_login.xml # Layout onde o usuário podera logar seus dados
   │   │   │   │   ├── activity_main.xml # Layout onde o usuário pode cadastrar ou logar seus dados atrávez do botão
   │   │   │   │   ├── activity_registrar # Layout onde o usuário podera cadastrar seus dados para serem salvos no Database
   │   │   │   └── values
   │   │   │       ├── strings.xml # Strings usadas no app
   │   │   │       ├── colors.xml # Cores definidas no projeto
   └── build.gradle # Configuração do Gradle
```

## Design e Prototipage
A interface do app foi criada usando ConstraintLayout no modelo Design para ser mais simples e facil de se usar e para ser mais compacto ao android e mais simples e pratico assim podendo se acostumar com o tempo.

## Telas do Aplicativo 

> Tela Principal

![image](https://github.com/user-attachments/assets/6f6f3715-6467-48e7-a7e3-4a077db8aa86)

Uma tela simples, as imagens são opicionais "Elas são colocadas por imagemView e selecione a pasta com as imagens pré-selecionadas", dois botões para trocar de telas, um para a tela de cadastrar os dados do usuário que serãos salvos e o outro levara para tela de logar o usuário podera logar com seu nome de usuário e senha criada.

> Tela de registrar

![image](https://github.com/user-attachments/assets/c8dcc00d-47e5-4ec6-ae1f-f953d81dbeeb)

Uma tela simples, as imagens são opicionais "Elas são colocadas por imagemView e selecione a pasta com as imagens pré-selecionadas", 4 EditText para, Nome real do usuário, Nome que o usuário usara para ser reconhecido e para logar no login, para cadastrar sua senha para ser logada, e para confirmar sua senha escolhida ou criada ao seu gosto e 2 botões, um para cadastrar e o para voltar a tela inicial.

> Tela de logar

![image](https://github.com/user-attachments/assets/6ead18c2-be5c-43e2-a382-d4fc914fca19)

Uma tela simples, as imagens são opicionais "Elas são colocadas por imagemView e selecione a pasta com as imagens pré-selecionadas", 2 EditText para, um para o nome de usuário falso criado e ooutro para a senha escolhida para ser logado com sucesso, 2 botões, um para cadastrar e o para voltar a tela inicial.

## Desenvolvedores
**Gabriel Henrique** - Desenvolvedor - [GitHub](https://github.com/Hacker19991).

## Licença
Este projeto está licenciado sob os termos da licença MIT. Para mais detalhes, veja o arquivo
[LICENSE](LICENSE).
