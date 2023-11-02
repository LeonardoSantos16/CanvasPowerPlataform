# Desafio de projeto - Criando um aplicativo do tipo Canvas com a Power Platform

Projeto criado a partir do desafio proposto no curso "**Criando um aplicativo do tipo Canvas com a Power Platform**" do Bootcamp  bootcamp Coding The Future Avanade  da Digital Innovation One em parceria com a Avanade. 

## Detalhes do bootcamp

Destinado a profissionais de tecnologia ou aspirantes que desejam aprimorar suas habilidades em C#, o programa oferece um caminho direto para o crescimento profissional e acesso às crescentes oportunidades do mercado de tecnologia.

Nesta trilha, você irá desenvolver suas habilidades com projetos práticos, desafios de códigos e mentorias com experts da Avanade. Além disso, você irá aprender a usar Inteligência Artificial (AI) e Machine Learning para desenvolver insights avançados e automatizar processos. 

## Requisitos do projeto

1. O aplicativo deverá ser criado no conceito Model Driven utilizando como Datasource o contexto do formulário em execução, apresentado nas aulas. Eis os requisitos desta primeira etapa:
   1. - Deverá conter Cabeçalho;
      - Deverá conter um campo de entrada de texto do tipo caixa de combinação (ComboBox) permitindo a seleção do curso;
      - Deverá conter Detalhe (componente do tipo Gallery);
      - O Campo de entrada de texto deve ser do tipo caixa de combinação (ComboBox), permitindo a seleção do instrutor.
2. Criar Fluxo do Power Automate.
3. Criar um fluxo para que, quando um novo registro de instrutor for criado, envie um e-mail (endereço do e-mail será o informado no cadastro do instrutor). 
4. Exportar o aplicativo e postar no portal classroom, juntamente com a planilha utilizada para carga dos dados dos estados.

### Canvas Alunos

Além dos requisitos do projeto foi criado uma entidade aluno e aluno x curso para a ligação entre entidades, um formulário tipo Canvas para os alunos presente em um curso e um fluxo do Power Automate

## Formulários canvas

O aplicativo criado no conceito Model Driven utilizando como Datasource o contexto do formulário em execução.

### <u>Tela principal</u>

Instrutores habilitados: 

- Cabeçalho com Título principal
- Botão Adicionar Instrutor/aluno (cabeçalho)
- Cabeçalho com nome das colunas
- Gallery exibindo os instrutores/aluno habilitados
- Campo com Nome do Instrutor/aluno
- Campo com o Nível do Instrutor
- Campo com o CPF do Aluno
- Campo com email do Aluno
- Botão para excluir instrutor/aluno (em cada linha da gallery)

### <u>Tela de adicionar</u>

Instrutores e alunos habilitados:

- Cabeçalho com Título principal
- Caixa de combinação (combobox) para seleção do instrutor ou aluno
- Rótulo para exibir Nível do instrutor selecionado
- Rótulo para exibir CPF do aluno selecionado
- Botão para cancelar a inclusão do instrutor/aluno
- Botão para salvar a inclusão do instrutor/aluno

### <u>Tela de excluir</u>

Instrutores e alunos habilitados:

- Cabeçalho com Título principal
- Rótulo com texto para conferência do instrutor/aluno a ser excluído
- Rótulo com o nome do instrutor/aluno a ser excluído
- Rótulo para exibir Nível do instrutor selecionado
- Rótulo para exibir CPF do aluno selecionado
- Botão para cancelar a exclusão do instrutor/aluno
- Botão para confirmar a exclusão do instrutor/aluno

## Power automate

Fluxo de ação do Power Automate no botão de salvar inclusão de instrutor/aluno para enviar um email do Outlook com informações sobre o instrutor/aluno adicionados no curso



## Projetos Coding The Future Avanade

Outros projetos feitos no Bootcamp Coding The Future Avanade:

Criação de um site básico utilizando o aplicativo Portals do Power Apps e o dataverse https://github.com/LeonardoSantos16/PortalPowerAppsDynamics

Criação de uma painel no power BI para a exibição no MS Dynamics https://github.com/LeonardoSantos16/PainelPowerBiDynamics365
