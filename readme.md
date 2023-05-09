<h1 align="center">CopiloTTeam</h1>

### Dor do cliente:

<p align="justify">Com base nas informações fornecidas no kick-off, é possível perceber que o cliente pode estar enfrentando desafios significativos na gestão de seus processos financeiros e comerciais. Entre as principais fontes de dor estão o cadastro manual de títulos e dados de endereço, a geração manual de relatórios de clientes adimplentes e inadimplentes por data de pagamento, data de crédito e data de vencimento, a complexidade do processamento de parcelas, a formatação de dados de moeda, a gestão de diferentes tipos de usuários e a baixa manual de parcelas. Para resolver esses problemas e alcançar um desempenho mais eficiente e satisfatório, o cliente precisa de uma solução que ofereça automatização, facilidade de uso e eficácia na gestão de suas operações.</p>

### Solução:

<p align="justify">A solução proposta é um sistema abrangente que inclui cadastro de clientes e gestão de títulos com parcelas, integrando-se à API dos correios para facilitar a inserção de dados de endereço. Com a capacidade de processar parcelas automaticamente em lote e fora do expediente, o sistema promove maior agilidade e eficiência. A segmentação em diferentes tipos de usuários, como comercial, financeiro e administrador, possibilita a criação e gestão centralizada de títulos e parcelas, adaptando-se às necessidades específicas de cada setor. Além disso, a mascara para moedas permite a formatação correta dos valores financeiros. Ademais, o sistema gera relatórios detalhados de clientes adimplentes e inadimplentes, com opções de filtragem por data de credito, de pagamento ou de vencimento. Com essa solução, o cliente pode aliviar suas dores e otimizar seu desempenho empresarial.</p>

> _Projeto baseado na metodologia ágil SCRUM, procurando desenvolver a Proatividade, Autonomia, Colaboração e Entrega de Resultados dos estudantes envolvidos_


<h1 align="center">
   🗓️ Sprints 
</h1>

|     Sprint     |     Status     |          Relatório          |
| :------------: | :-----------: | :-------------------------: |
|      Sprint 1  |    Concluída  |   <a href="https://github.com/CopiloTTeam/documentacao/blob/main/Docs/Relatórios%20de%20Sprint/CopilotTeam%20-%20Sprint%201%2013032023%20à%2002042023.md">Clique Aqui</a>         |
|      Sprint 2  |    Concluída  |  <a href="https://github.com/CopiloTTeam/documentacao/blob/main/Docs/Relatórios%20de%20Sprint/CopilotTeam%20-%20Sprint%202%2003042023%2023042023.md">Clique Aqui</a>  |
|      Sprint 3  |   Iniciada     | <a href="#">Clique Aqui</a>  |
|      Sprint 4  |    Não Iniciada    | <a href="#">Clique Aqui</a>  |


<h1 align="center">🗃️ Backlog do Produto</h1>

<p>Com base no kickoff feito pelo cliente, foi criado um backlog do produto. Esse backlog foi priorizado e dividido em sprints, com o objetivo de permitir a entrega incremental de valor ao cliente ao longo do tempo.</p>


<table style="width:100%; table-layout: fixed;">
    <thead>
        <th style="width: 15%; text-align: center;">RF</th>
        <th style="width: 15%; text-align: center;">Prioridade</th>
        <th style="width: 28%; text-align: center;">Descrição</th>
        <th style="width: 13%; text-align: center;">Sprint</th>
        <th style="width: 10%; text-align: center;">Status</th>
    </thead>
    <tbody>
        <tr>
            <td style="text-align: center; vertical-align: middle;">RF 001</td>
            <td style="text-align: center; vertical-align: middle;">1</td>
            <td style="text-align: center; vertical-align: middle;">Gerenciamento de Clientes</td>
            <td style="text-align: center; vertical-align: middle;">1</td>
            <td style="text-align: center; vertical-align: middle;">✅</td>
        </tr>
        <tr>
            <td style="text-align: center; vertical-align: middle;">RF 002</td>
            <td style="text-align: center; vertical-align: middle;">1</td>
            <td style="text-align: center; vertical-align: middle;">Gerenciamento de Títulos</td>
            <td style="text-align: center; vertical-align: middle;">1</td>
            <td style="text-align: center; vertical-align: middle;">✅</td>
        </tr>
        <tr>
            <td style="text-align: center; vertical-align: middle;">RF 003</td>
            <td style="text-align: center; vertical-align: middle;">1</td>
            <td style="text-align: center; vertical-align: middle;">Gerenciamento de Funcionários</td>
            <td style="text-align: center; vertical-align: middle;">1</td>
            <td style="text-align: center; vertical-align: middle;">✅</td>
        </tr>
        <tr>
            <td style="text-align: center; vertical-align: middle;">RF 004</td>
            <td style="text-align: center; vertical-align: middle;">2</td>
            <td style="text-align: center; vertical-align: middle;">Consulta de endereço por CEP na API dos Correios e Segurança</td>
            <td style="text-align: center; vertical-align: middle;">2</td>
            <td style="text-align: center; vertical-align: middle;">✅</td>
        </tr>
        <tr>
            <td style="text-align: center; vertical-align: middle;">RF 005</td>
            <td style="text-align: center; vertical-align: middle;">3</td>
            <td style="text-align: center; vertical-align: middle;">Relatório de Cobranças</td>
            <td style="text-align: center; vertical-align: middle;">3</td>
            <td style="text-align: center; vertical-align: middle;">🟥</td>
        </tr>
       <tr>
            <td style="text-align: center; vertical-align: middle;">RF 006</td>
            <td style="text-align: center; vertical-align: middle;">4</td>
            <td style="text-align: center; vertical-align: middle;">Processamento Batch</td>
            <td style="text-align: center; vertical-align: middle;">4</td>
            <td style="text-align: center; vertical-align: middle;">🟥</td>
        </tr>
    </tbody>
</table>
<small>A prioridade do backlog foi definida utilizando numeros de 1 a 4, sendo o número 1 o mais importante e o 4 o menos importante.</small>




<h1 align="center">🗂️ User Stories</h1>

<table>
  <thead>
    <tr>
      <th style="width: 15%; text-align: center;">Épico</th>
      <th style="width: 15%; text-align: center;">Ator</th>
      <th style="width: 15%; text-align: center;">Ação</th>
      <th style="width: 15%; text-align: center;">Motivo</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td rowspan="2" style="text-align: center; vertical-align: middle;">RF 001 - Gerenciamento de Clientes</td>
      <td style="text-align: center; vertical-align: middle;">Administrador</td>
      <td style="text-align: center; vertical-align: middle;">Cria, procura, atualiza e delete usuários do sistema.</td>
      <td style="text-align: center; vertical-align: middle;">Eu como administrador quero poder gerenciar um usuário em meu sistema.</td>
    </tr>
    <tr>
      <td style="text-align: center; vertical-align: middle;">Comercial</td>
      <td style="text-align: center; vertical-align: middle;">Cria, procura e atualiza usuários do sistema.</td>
      <td style="text-align: center; vertical-align: middle;">Eu como comercial quero poder criar, atualizar e ver os usuários que cadastrei no sistema.</td>
    </tr>
    <tr>
      <td rowspan="4" style="text-align: center; vertical-align: middle;">RF 002 - Gerenciamento de Títulos</td>
      <td style="text-align: center; vertical-align: middle;">Administrador</td>
      <td style="text-align: center; vertical-align: middle;">Cria, edita, procura e deleta titulos do sistema</td>
      <td style="text-align: center; vertical-align: middle;">Eu como administrador queri poder gerenciar um título do meu sistema</td>
    </tr>
    <tr>
      <td style="text-align: center; vertical-align: middle;">Administrador</td>
      <td style="text-align: center; vertical-align: middle;">Da baixa em parcela</td>
      <td style="text-align: center; vertical-align: middle;">Eu como administrador quero poder dar baixa em uma parcela de um título de meu sistema.</td>
    </tr>
    <tr>
      <td style="text-align: center; vertical-align: middle;">Comercial</td>
      <td style="text-align: center; vertical-align: middle;">Cria, edita e procura titulos do sistema.</td>
      <td style="text-align: center; vertical-align: middle;">Eu como comercial quero poder criar, editar e ver os titulos que gerei.</td>
    </tr>
      <tr>
      <td style="text-align: center; vertical-align: middle;">Financeiro</td>
      <td style="text-align: center; vertical-align: middle;">Da baixa em parcela</td>
      <td style="text-align: center; vertical-align: middle;">Eu como financeiro quero poder dar baixa nas parcelas que foram pagas pelos clientes no sistema.</td>
    </tr>
      <tr>
      <td rowspan="5" style="text-align: center; vertical-align: middle;">RF 003 - Gerenciamento de Funcionários</td>
      <td style="text-align: center; vertical-align: middle;">Administrador</td>
      <td style="text-align: center; vertical-align: middle;">Deleta funcionario do sistema e/ou altera cargo</td>
      <td style="text-align: center; vertical-align: middle;">Eu como administrador quero poder alterar o cargo e/ou deletar um funcionario de meu sistema</td>
    </tr>
      <tr>
      <td style="text-align: center; vertical-align: middle;">Administrador</td>
      <td style="text-align: center; vertical-align: middle;">Aceita novos funcionarios no sistema e define cargos a eles.</td>
      <td style="text-align: center; vertical-align: middle;">Eu como administrador quero poder aceitar novos funcionários no sistema e definir cargos a eles.</td>
    </tr>
      <tr>
      <td style="text-align: center; vertical-align: middle;">Administrador</td>
      <td style="text-align: center; vertical-align: middle;">Loga no sistema</td>
      <td style="text-align: center; vertical-align: middle;">Eu como administrador quero poder logar no sistema.</td>
    </tr>
      <tr>
      <td style="text-align: center; vertical-align: middle;">Financeiro</td>
      <td style="text-align: center; vertical-align: middle;">Loga no sistema</td>
      <td style="text-align: center; vertical-align: middle;">Eu como financeiro quero poder logar no sistema.</td>
    </tr>
      <tr>
      <td style="text-align: center; vertical-align: middle;">Comercial</td>
      <td style="text-align: center; vertical-align: middle;">Loga no sistema</td>
      <td style="text-align: center; vertical-align: middle;">Eu como comercial quero poder logar no sistema.</td>
    </tr>
      <tr>
      <td rowspan="3" style="text-align: center; vertical-align: middle;">RF 004 - Consulta de endereço por CEP na API dos Correios</td>
      <td style="text-align: center; vertical-align: middle;">Administrador</td>
      <td style="text-align: center; vertical-align: middle;">Cadastra endereço de clientes a partir do CEP</td>
      <td style="text-align: center; vertical-align: middle;">Eu como administrador quero poder cadastrar um endereço de cliente a partir do CEP dele.</td>
    </tr>
      <tr>
      <td style="text-align: center; vertical-align: middle;">Comercial</td>
      <td style="text-align: center; vertical-align: middle;">Cadastra endereço de clientes a partir do CEP</td>
      <td style="text-align: center; vertical-align: middle;">Eu como comercial quero poder cadastrar um endereço de cliente a partir do CEP dele.</td>
    </tr>
    </tr>
      <tr>
      <td style="text-align: center; vertical-align: middle;">Sistema</td>
      <td style="text-align: center; vertical-align: middle;">Deixa o sistema segura contra invasões</td>
      <td style="text-align: center; vertical-align: middle;">Eu como sistema, preciso ser seguro para que meus usuários possam fazer bom uso de mim.</td>
    </tr>
      <tr>
      <td rowspan="2" style="text-align: center; vertical-align: middle;">RF 005 - Relatório de Cobranças</td>
      <td style="text-align: center; vertical-align: middle;">Administrador</td>
      <td style="text-align: center; vertical-align: middle;">Vê o relatório completo de cobranças</td>
      <td style="text-align: center; vertical-align: middle;">Eu como administrador quero poder ver o relatório completo de cobranças, mostrando os clientes adimplentes e inadimplentes.</td>
    </tr>
      <tr>
      <td style="text-align: center; vertical-align: middle;">Comercial</td>
      <td style="text-align: center; vertical-align: middle;">Vê o relatório parcial de cobranças</td>
      <td style="text-align: center; vertical-align: middle;">Eu como comercial quero poder ter acesso ao relatório de clientes inadimplentes afim de cobrar os pagamentos dos clientes.</td>
    </tr>
      <tr>
      <td rowspan="1" style="text-align: center; vertical-align: middle;">RF 006 - Processamento Batch</td>
      <td style="text-align: center; vertical-align: middle;">Sistema</td>
      <td style="text-align: center; vertical-align: middle;">Processa parcelas de titulos depois do expediente.</td>
      <td style="text-align: center; vertical-align: middle;">Eu como sistema preciso que o processamento de parcelas seja feito em lote e depois do expediente afim de garatir o bom funcionamento do sistema.</td>
    </tr>
  </tbody>
</table>

<h1 align="center">📝 Regras de Negocio </h1>

### Processamento Batch:

<p align="justify">⚫ O processamento de títulos para a criação de 12 parcelas deve ser realizado por meio de processamento em lote, também conhecido como processamento batch. Esse tipo de processamento é caracterizado pela execução de um conjunto de tarefas simultaneamente, de forma automática e programada, a partir de um gatilho previamente definido.</p>

<p align="justify">Além disso, é fundamental ressaltar que o gatilho para o processamento de títulos deve ser acionado fora do período de expediente, a fim de evitar interrupções ou interferências no fluxo de trabalho diário. Para tanto, é recomendável que o gatilho seja programado para ser ativado em um horário em que as atividades do negócio sejam menos intensas e que a execução das tarefas de processamento em lote seja concluída antes do início do expediente.</p>

<p align="justify">Dessa forma, o processamento de títulos poderá ser realizado de maneira mais eficiente e produtiva, proporcionando benefícios tanto para a empresa quanto para os clientes envolvidos. Além disso, a adoção do processamento batch permite uma maior automatização dos processos e a redução de possíveis erros humanos, contribuindo para a melhoria da qualidade dos serviços prestados.</p>

### Divisão de Perfis:

<p align="justify">🟢 A fim de garantir uma gestão adequada e segura do sistema, é recomendável que ele seja dividido em perfis específicos de acesso. Dessa forma, sugere-se a criação de três perfis distintos: administrador, comercial e financeiro.</p>

<p align="justify">O perfil de administrador possui acesso irrestrito a todas as funcionalidades do sistema, podendo realizar todas as operações disponíveis, desde a criação e edição de informações até o controle de acesso de outros usuários.</p>

<p align="justify">Já o perfil comercial tem como responsabilidade principal a gestão de clientes e parcelas. Nesse sentido, esse usuário pode criar, editar e pesquisar informações de clientes, bem como criar, editar e pesquisar informações de parcelas. Vale ressaltar que o perfil comercial não tem acesso a operações financeiras, como baixa em parcelas.</p>

<p align="justify">Por sua vez, o perfil financeiro é responsável pela baixa em parcelas e pela consulta de clientes e títulos criados. Esse usuário não pode criar ou editar informações de clientes ou parcelas, tendo seu acesso limitado apenas a operações financeiras pontuais.</p>

<p align="justify">Com a divisão do sistema em perfis específicos, é possível garantir uma gestão mais eficiente e segura, evitando o acesso indevido a informações sensíveis e garantindo que cada usuário tenha acesso somente às informações e funcionalidades relevantes para o seu trabalho.</p>

### Formatação para Moedas:

<p align="justify">🔴 A fim de garantir a conformidade com os padrões internacionais, recomenda-se que a formatação de moedas seja realizada da esquerda para a direita. Essa prática é adotada mundialmente e permite uma padronização eficiente na exibição e interpretação de valores monetários.</p>

<p align="justify">Ao adotar a formatação de moedas da esquerda para a direita, é possível minimizar eventuais problemas de compreensão ou interpretação equivocada de valores, facilitando a visualização e entendimento do montante envolvido.</p>

<p align="justify">Ademais, é importante destacar que a adoção de padrões internacionais contribui para a compatibilidade do sistema com outros sistemas e processos que adotam a mesma formatação, permitindo uma maior eficiência e interoperabilidade em transações financeiras e comerciais.</p>

<p align="justify">Portanto, a adoção da formatação de moedas da esquerda para a direita é uma prática recomendada e pode trazer benefícios significativos para a gestão financeira e para a integração com outros sistemas.</p>
