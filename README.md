# todo-list

<h1 align="center">Aplicativo de Lista de Tarefas (To-Do List)</h1>

<h3>🖊 Descrição</h3>
<p>Este é um aplicativo simples de lista de tarefas (To-Do List) que permite aos usuários adicionar, marcar como concluído e excluir tarefas. As tarefas são armazenadas no localStorage do navegador, permitindo que persistam mesmo após a página ser recarregada. O aplicativo também inclui um filtro para visualizar todas as tarefas, apenas as concluídas ou apenas as pendentes.</p>
<h2>Funcionalidades</h2>
<b>1. Adicionar Tarefa:</b>
<p>Digite a tarefa no campo de entrada e clique no botão de adicionar. A tarefa será exibida na lista e salva no localStorage.<p>
<b>2. Marcar como Concluído:</b>
<p>Clique no botão de check (✓) para marcar a tarefa como concluída. A tarefa será destacada visualmente.</p>
<b>3. Excluir Tarefa:</b>
<p>Clique no botão de lixeira (🗑️) para remover a tarefa da lista e do localStorage.</p>
<b>4. Filtrar Tarefas:<b>
<p>Use o menu suspenso para filtrar as tarefas por:</p>
<li>Todas: Exibe todas as tarefas.</li>
<li>Concluídas: Exibe apenas as tarefas marcadas como concluídas.</li>
<li>Pendentes: Exibe apenas as tarefas não concluídas.</li>
<br>
<h2>Estrutura do Código</h2>
<p>Seletores: Seleciona os elementos HTML necessários.</p>
<p>Event Listeners: Configura os ouvintes de eventos para interações do usuário.</p>
<br>
<h2>Funções:</h2>
<li>addTodo: Adiciona uma nova tarefa à lista e ao localStorage.</li>
<li>deleteCheck: Gerencia a exclusão e marcação de tarefas como concluídas.</li>
<li>filterTodo: Filtra as tarefas com base na seleção do usuário.</li>
<li>salveLocalTodos: Salva as tarefas no localStorage.</li>
<li>getTodos: Carrega as tarefas do localStorage ao iniciar a página.</li>
<li>removeLocalTodos: Remove tarefas do localStorage.</li>
<br>
<h2>Como Usar</h2>
<p>1. Abra o arquivo index.html em um navegador.</p>
<p>2. Adicione tarefas usando o campo de entrada e o botão de adicionar.</p>
<p>3. Interaja com as tarefas usando os botões de check e lixeira.</p>
<p>4. Use o filtro para visualizar as tarefas conforme necessário.</p>
