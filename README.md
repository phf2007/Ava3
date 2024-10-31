# Ava3

> Um aplicativo Android simples que funciona como um ifood mas pra hamburger.

## 📱 Descrição

O **Ava3** permite ao usuário comprar hamburger, usando uma conta própria.

## 🔧 Funcionalidades

- [x] 3 Telas
- [x] Garante segurança
- [x] Fácil de usar
- [x] Interface simples e intuitiva
- [ ] Tema claro e escuro (planejado para futuras versões)

## 🚀 Tecnologias Utilizadas

- [x] **Android Studio** (Bumblebee | 2021.1.1)
- [x] **Java** para desenvolvimento
- [x] **ConstraintLayout** para interface responsiva
- [x] **TextView**, **Button**, **ImageViewer** e **EditText**

## 🛠️ Como Rodar o Projeto

Siga os passos abaixo para rodar o projeto localmente:


1. Clone este repositório:
    ```bash
    git clone https://github.com/phf2007/Calculadora/primeiroApp.zip
    ```

2. Abra o projeto no Android Studio.

3. Compile e execute o projeto em um emulador ou dispositivo físico.

## 📂 Estrutura do Projeto

AppProva3
├── app
│   ├── main
│   │   ├── java/com.example.appprova3
│   │   │   ├── CatalogoActivity.java              # Atividade principal da tela do catálogo
│   │   │   ├── CadastroActivity.java              # Atividade principal da tela de cadastro 
│   │   │   ├── DatabaseHelper.java                # Atividade que salva as contas
│   │   │   ├── LoginActivity.java                 # Atividade principal da tela de login
│   │   ├── res
│   │   │   ├── layout
│   │   │   │   ├── activity_cadastro.xml          # Layout da tela de cadastro
│   │   │   │   ├── activity_login.xml             # Layout da tela de login
│   │   │   │   ├── activity_catalogo.xml          # Layout da tela de catalogo
│   │   │   └── values
│   │   │       ├── strings.xml                    # Strings usadas no app
│   │   │       ├── colors.xml                     # Cores definidas no projeto
│   └── build.gradle                               # Configuração do Gradle
└── README.md                                      # Este arquivo



## 🎨 Design e Prototipagem 

A interface do app foi criada usando **ConstraintLayout** para manter a responsividade em diferentes tamanhos de tela. 

O design é minimalista e fácil de usar, com foco na simplicidade.

 ## 🖥️ Telas do Aplicativo

**Tela Login** 

Na tela de login, teremos dois botões, um para ir para a tela de cadastro e o outro que entra na conta, acima tem dois EditText respectivamente de email e senha.

**Tela Catálogo** 

Na tela de catálogo teremos um botão no topo para fazer o pedido pelo whats, abaixo temos o menu, com hamburgeres, energeticos e etc.

**Tela Cadastro** 

Na tela de cadastro temos 4 EditText, nome, email, senha e repetir senha, além do botão de confirmar.

## 👨‍💻 Desenvolvedores – 
Pedro Henrique Fontes - Desenvolvedor - [GitHub](https://github.com/phf2007)
