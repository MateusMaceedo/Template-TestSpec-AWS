## Template TestSpec

Projeto com diversos exemplos de aplicações automatizadas em diferentes cenários utilizando tecnologias distintas. O foco desse repositório é propagar o conhecimento da configuração dos testspecs de usuários para estabelecer uma melhor experiência e um melhor entendimento de como iniciar a configuração desse arquivo essencial dos testes automatizados na AWS.

- O que é o "testspec.yml" ?
> O testspec é o arquivo lido pela etapa "TestRun" existente no stage do (ContinuosTest), essa etapa é representada por codebuild que a partir da configuração do testspec cria o ambiente serveless adequado para executar e gerar um relatório baseado no resultado dos seus testes.

#### Branchs

- Abaixo segue a tabela sumário com o link dos exemplos de template que temos nesse projeto.

| **Nome da Branch**                                              | **Tipo de Teste** | **Tipo Pipeline** | **Descrisão** |
| ----------------------------------------------------------------|-------------------|-------------------|---------------|

#### Onde executar?

Os códigos de teste na AWS não executados na etapa ContinuosTest, no estagio chamado TestRun, que executa o TestSpec, que é um arquivo BuildSpec do CodeBuild ( [Documentação AWS]() ) para gerar os testes.

Nesse arquivo, é necessário para executar os nossos testesm especificar linguagem/runtime que será utilizado( [Versões da AWS]() ), e os comandos necessários para executar a instação das dependências (phase->install) e execução do teste (phase->build).

<a href="https://www.linkedin.com/in/mateus-macedo-937a32163/">
 <img style="border-radius:50%" width="100px; "src="https://avatars.githubusercontent.com/u/63172367?s=460&u=11fd26ea8a7f5663d7707d7ef254e4f8bfca1b05&v=4"/>
 <p>Mateus Macedo</p>
</a>
