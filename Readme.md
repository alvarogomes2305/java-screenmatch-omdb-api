# 🎬 ScreenMatch - Busca de Filmes com API OMDb

Projeto desenvolvido durante a **Carreira Java** da **Alura**, no curso **"Java: consumindo API, gravando arquivos e lidando com erros"**.

A aplicação realiza consultas na **API OMDb**, permitindo buscar informações de filmes, converter os dados recebidos em objetos Java utilizando a biblioteca **Gson** e gerar arquivos JSON com os resultados das consultas.

---

## 📸 Demonstração

### Estrutura do projeto

<img src="imagens/EstruturaDoProjeto.png" width="800"/>

### Busca de filmes

<img src="imagens/TestePrincipal.png" width="800"/>

### Resultado da busca

<img src="imagens/TestePrincipalComBusca.png" width="800"/>

### Manipulação de listas

<img src="imagens/TestePrincipalComLista.png" width="800"/>


---

# 🚀 Funcionalidades

- 🔍 Buscar filmes através da API OMDb
- 🌐 Consumir APIs REST utilizando HttpClient
- 📦 Converter JSON em objetos Java com Gson
- 📄 Serializar objetos para JSON
- 💾 Gerar arquivos JSON automaticamente
- ⚠️ Tratar exceções personalizadas
- 📚 Manipular listas de objetos
- 🏗️ Organização do projeto em pacotes
- ☕ Aplicação desenvolvida utilizando Java moderno (Records)

---

# 🛠️ Tecnologias utilizadas

- Java 21
- Gson
- API OMDb
- HttpClient
- HttpRequest
- HttpResponse
- JSON
- IntelliJ IDEA
- Git
- GitHub

---

# 📂 Estrutura do projeto

```
src
│
├── calculos
│   ├── CalculadoraDeTempo.java
│   └── FiltroRecomendacao.java
│
├── excecao
│   └── ErroDeConversaoDeAnoException.java
│
├── modelos
│   ├── Filme.java
│   ├── Serie.java
│   ├── Titulo.java
│   ├── TituloOmdb.java
│   └── Episodio.java
│
└── principal
    ├── Principal.java
    ├── PrincipalComBusca.java
    ├── PrincipalComLista.java
    └── Teste.java
```

A organização em pacotes facilita a manutenção do código e segue boas práticas de desenvolvimento em Java.

---

# 📖 Conceitos aplicados

Durante o desenvolvimento deste projeto foram praticados conceitos como:

- Programação Orientada a Objetos
- Consumo de APIs REST
- Manipulação de JSON
- Serialização e desserialização
- Records
- Tratamento de exceções
- Exceptions personalizadas
- Escrita de arquivos
- Organização em pacotes
- Coleções em Java

---

# 🌐 API utilizada

Este projeto utiliza a API pública da **OMDb (Open Movie Database)** para realizar consultas de filmes.

Documentação:

https://www.omdbapi.com/

---

# ▶️ Como executar

## Clone o repositório

```bash
git clone https://github.com/SEU-USUARIO/java-screenmatch-omdb-api.git
```

## Abra o projeto

Abra o projeto utilizando sua IDE de preferência (IntelliJ IDEA recomendado).

## Adicione a biblioteca Gson

Baixe o arquivo **gson.jar** e adicione-o às dependências do projeto.

## Configure sua API Key

No código, substitua pela sua chave da API OMDb:

```java
String endereco =
"https://www.omdbapi.com/?t=" + busca.replace(" ", "+") + "&apikey=SUA_API_KEY";
```

## Execute

Execute uma das classes da pasta:

```
principal
```

como, por exemplo:

- PrincipalComBusca
- PrincipalComLista

---

# 📚 Aprendizados

Este projeto permitiu colocar em prática conhecimentos importantes para o desenvolvimento Java, como integração com APIs externas, manipulação de JSON, tratamento de erros, escrita de arquivos e organização de aplicações em camadas.

Foi uma excelente oportunidade para compreender como aplicações reais consomem serviços externos e transformam os dados recebidos em objetos Java.

---

# 👨‍💻 Autor

**Álvaro**

🔗 LinkedIn:

https://www.linkedin.com/in/alvaro-gomes-500139331/


---

# 🙏 Agradecimentos

Projeto desenvolvido durante o curso **"Java: consumindo API, gravando arquivos e lidando com erros"** da **Carreira Java** da **Alura**.

Agradecimento especial aos instrutores **Paulo Silveira** e **Jacqueline Oliveira**, pelos ensinamentos e pela excelente didática durante o curso.

---

⭐ Se este projeto foi interessante para você, deixe uma ⭐ no repositório!
