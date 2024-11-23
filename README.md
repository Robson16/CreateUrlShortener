# URL Shortener API - Projeto Java 🚀

Este projeto foi desenvolvido durante o evento da **Rocketseat**, utilizando a arquitetura serverless para criar uma API de encurtamento de URLs dinâmica e escalável, integrando serviços como **AWS Lambda** e **Amazon S3**.

---

## 🔍 Descrição

### Aula 01 - Criando Função Serverless e Configurando URL Encurtada
Nesta etapa, criamos nossa primeira função serverless na **AWS Lambda** e configuramos o ambiente inicial do projeto. Aqui estão os principais passos:
- Criamos uma conta na **AWS** e aprendemos sobre a importância das funções serverless em sistemas escaláveis.
- Desenvolvemos a função `createShortUrlLambda`, que:
    - Recebe requisições HTTP.
    - Processa os dados fornecidos para gerar uma URL encurtada dinâmica.
- Consolidamos o aprendizado através de exemplos práticos, configurando o ambiente e aprendendo a manipular requisições de forma eficiente.

### Aula 02 - Integração com Amazon S3
No segundo momento, integramos nosso sistema com o **Amazon S3**, adicionando funcionalidades para armazenamento seguro e escalável. As principais atividades incluem:
- Criação de um bucket no S3 para armazenar os dados gerados.
- Conexão da função `createShortUrlLambda` com o bucket.
- Implementação de geração de UUIDs únicas para cada URL encurtada.
- Testes para validar o comportamento e a integração do sistema.

---

## 🛠️ Tecnologias e Dependências

O projeto utiliza as seguintes tecnologias e bibliotecas:

- **AWS Lambda Java Core**: Para construção de funções serverless.
- **AWS Lambda Java Log4j2**: Para gerenciamento de logs.
- **Amazon S3 SDK**: Para integração com o Amazon S3.
- **Lombok**: Para simplificar o código com anotações.
- **Jackson Databind**: Para manipulação de JSON.

### Configuração do Maven:
- **Java 17** como versão do compilador.
- **Maven Shade Plugin** para empacotar o projeto.

---

## 🚀 Como Executar

1. Clone este repositório:
   ```bash
   git clone https://github.com/Robson16/nlw17-inorbit-nodejs.git
   ```

2. Configure suas credenciais da AWS para acessar os serviços necessários.

3. Compile o projeto:
    ```
   mvn clean package
   ```
4. Implante as funções Lambda na AWS e configure os triggers necessários.
5. Teste as funcionalidades através de uma ferramenta como Postman ou curl.

## 🌐 Referências e Links

- [AWS Lambda](https://aws.amazon.com/pt/lambda/)
- [Amazon S3](https://aws.amazon.com/pt/s3/)

##💻 Desenvolvido por Robson Henrique Rodrigues durante o evento *Curso Gratuito de Java* da Rocketseat. 🧑‍💻