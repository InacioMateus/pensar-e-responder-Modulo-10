# Modificações no Código

## ListarTarefa.jsx
1. Adição dos estados 'historicoTarefas' e 'mostrarHistorico' para controlar o histórico de tarefas.
2. Adição do botão "Mostrar Histórico" para alternar a exibição do histórico de tarefas.
3. Criação de um segundo bloco de tabela para exibir o histórico de tarefas quando 'mostrarHistorico' é true.
4. Modificação da lógica de exclusão para mover tarefas concluídas para o histórico.

## Criação do AlertDialog.jsx
1. Cria um novo componente 'AlertDialog' para exibir um diálogo de confirmação.
2. Recebe as props 'open', 'handleClose', 'handleConfirm', 'title', e 'description'.
3. Utiliza o componente 'Dialog' do Material-UI para exibir o diálogo.
4. Exibe um título e uma descrição no corpo do diálogo.
5. Adiciona botões de ação para confirmar ou cancelar a operação.

## Adição do Componente AlertDialog no ListarTarefa.jsx

1. Adição do componente 'AlertDialog' para mostrar um diálogo de confirmação antes de excluir uma tarefa.
2. Implementação do componente 'AlertDialog' para exibir um diálogo de confirmação ao tentar excluir uma tarefa.
3. Implementação a lógica para abrir e fechar o diálogo de confirmação.



# Modificações dos estilos 

## App.css
1. Adiciona classes .table-row-even e .table-row-odd para estilizar as linhas da tabela alternadamente.