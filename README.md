<!-- Configuração do git README.md no site: https://docs.github.com/pt/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax-->

# edu-jira-configuracao
Repositório público sobre configuração, processos, dados do Jira, aqui estarão dicas e dados de configurações e
informações que estarei realizando na configuração do Jira, conforme meu aprendizado sobre a ferramenta.

<h1> O que é Jira</h1>

<p>É uma ferramenta que permite o monitoramento de tarefas e acompanhamento de projetos garantindo o gerenciamento de todas as suas atividades em único lugar.</p>

<p> Faz filtros para pesquisa avançada através do JQL (JIRA Query Language).</p>

<h2> Conheça a sintaxe JQL</h2>

<div style="display: inline_block"><br>
    <img align="center" alt="Rafa-Ts" height="200" width="500"
        src="https://github.com/Marilainny/edu-jira-configuracao/blob/main/imagem/sintaxe-JQL.png">
</div>

<h1>Tipos de Serviços para equipes de T.I</h1>
<p style='text-align: justify;'>Alguns serviços que poderão ser adicionados a conta principal.</p>

<h2>JIRA SERVICE DESK</h2>
<p> Cliente abre o chamado, pode interagir diretamente com a equipe, recebe notificações automáticas, tem o controle de satisfação com o cliente e prover relatórios diversos. Criar fluxo de trabalho com a aprovação do cliente.
</p>

<h3>Adaptar o processo ITIL(<i>Information Technology Infrastructure Library</i>)</h3>

<p>Um conjunto de práticas detalhadas para gerenciamento de serviços de TI que se concentra no alinhamento de serviços de TI com as necessidades dos negócios. O ITIL descreve processos, procedimentos, tarefas e listas de verificação que não são específicos da organização nem específicos da tecnologia, mas podem ser aplicados por uma organização para estabelecer a integração com a estratégia da organização, entregando valor e mantendo um nível mínimo de competência.</p>

<img align="center" alt="Rafa-Ts" height="450" width="900"
    src="https://github.com/Marilainny/edu-jira-configuracao/blob/main/imagem/ITIL-Processes.jpg">
</p>

<h2>JIRA SOFTWARE</h2>

<p>O Jira software tem a metodologia ágil Scrum e Kaban. Ao implementar a metodologia ágil e o DevOps, o Kanban e o
    Scrum oferecem metodologias diferentes para gerenciar trabalhos complexos.</P>
<h2>Kaban</h2>
<p>Kanban tem a ver com visualizar seu trabalho, limitar o trabalho em andamento e maximizar a eficiência (ou fluxo).Para alcançar esse objetivo, elas usam o quadro Kanban e melhoram sempre o fluxo de trabalho.</p>

<img align="center" alt="Rafa-Ts" height="400" width="700"
    src="https://github.com/Marilainny/edu-jira-configuracao/blob/main/imagem/JIRA-modelo%20Kaban.png">

<h2>Scrum</h2>

<p>As equipes Scrum têm o compromisso de lançar software funcional em intervalos definidos chamados sprints. O objetivo é criar ciclos de aprendizagem para reunir e integrar com rapidez o feedback dos clientes.</p>

<p>As equipes Scrum adotam papéis específicos, criam artefatos especiais e realizam cerimônias regulares para manter o avanço das coisas.</p>

<img align="center" alt="Rafa-Ts" height="400" width="700"
    src="https://github.com/Marilainny/edu-jira-configuracao/blob/main/imagem/JIRA-modelo-Scrum.png">

<h2>Diferença entre Scrum e Kaban</h2>
<table>
    <tr>
        <td></td>
        <td><strong>Scrum</strong></td>
        <td><strong>Kanban</strong></td>
    </tr>
    <tr>
        <td><strong>Origem</strong></td>
        <td>Desenvolvimento de software</td>
        <td>Manufatura enxuta</td>
    </tr>
    <tr>
        <td><strong>Ideologia</strong></td>
        <td>Aprendizado através de experiências, auto-organização e priorização, e reflexão sobre vitórias e derrotas
            para melhorar continuamente.</td>
        <td>Usa recursos visuais para melhorar o trabalho em andamento</td>
    </tr>
    <tr>
        <td><strong>Cadence</strong></td>
        <td>Sprints regulares de duração fixa (ou seja, duas semanas)</td>
        <td>Fluxo contínuo</td>
    </tr>
    <tr>
        <td><strong>Práticas</strong></td>
        <td>Planejamento de sprint, sprint, scrum diário, revisão de sprint, retrospectiva de sprint</td>
        <td>Visualize o fluxo de trabalho, limite o trabalho em andamento, gerencie o fluxo, incorpore ciclos de
            feedback</td>
    </tr>
    <tr>
        <td><strong>Funções</strong></td>
        <td>Product owner, scrum master, equipe de desenvolvimento</td>
        <td>Nenhuma função necessária</td>
    </tr>
</table>
<h2>Epics</h2>
<p>Um epic ágil é uma quantidade de trabalho que pode ser dividida em tarefas específicas (chamadas de histórias do usuário) com base nas necessidades/solicitações dos clientes ou usuários finais. Ao adotar a agilidade e o DevOps, um epic serve para gerenciar tarefas. Os epics são uma maneira útil de criar uma hierarquia. De uma perspectiva prática, ele é o nível superior da hierarquia de trabalho.</p>

<p>Os epics geralmente englobam várias equipes, em vários projetos, e podem até ser monitorados em vários quadros.</p>

<h2>Divisão de um epic ágil</h2>
<p>O roteiro de produto é um plano de ação de como vai ser o desenvolvimento de um produto ou uma solução ao longo do  tempo. É importante vincular o trabalho da equipe ao roteiro. Um modo consagrado de fazer isso é dividir as iniciativas em epics na lista de pendências do produto e, depois, decompô-las em requisitos e histórias de usuários.</p>

<img align="center" alt="Rafa-Ts" height="400" width="700"
    src="https://github.com/Marilainny/edu-jira-configuracao/blob/main/imagem/Roteiro.png">

<p>Divida as iniciativas em epics no backlog do produto, depois divida ainda mais em requisitos e histórias de usuários. Com essa hierarquia de itens, é mais fácil para os proprietários de produtos e a equipe de desenvolvimento tomar decisões e entender como o trabalho se encaixa no cenário geral.</p>

<p>Documento de Requisitos do Produto (PRD, na sigla em inglês) - Um documento de requisitos do produto define o produto que você está prestes a criar: ele descreve a finalidade do produto, seus recursos, funcionalidades e omportamento.</p>

<p>Use o Confluence para criar requisitos de produto com o template do documento de requisitos do produto.</p>

<ol type="1">
    <li>Defina as especificidades do projeto.</li>
    <li>Metas da equipe e objetivos de negócios.</li>
    <li>Contexto e ajuste estratégico.</li>
    <li>Suposições - Liste as suposições técnicas, comerciais ou de usuário que você pode estar fazendo.</li>
    <li>Histórias de usuário</li>
    <li>Interação dos usuários e design</li>
    <li>Perguntas</li>
    <li>O que não estamos fazendo - Sinalize o que está fora do escopo no momento</li>
</ul>
<h2>Exemplo de um PRD de uma página</h2>
<p>Modelo de um documento de requisitos de produto muito detalhado criado usando o Confluence. </p>

<img align="center" alt="Rafa-Ts" height="900" width="900"
    src="https://github.com/Marilainny/edu-jira-configuracao/blob/main/imagem/ModeloPRD.png">

<img align="center" alt="Rafa-Ts" height="900" width="900"
    src="https://github.com/Marilainny/edu-jira-configuracao/blob/main/imagem/ModeloPRD-design.png">
