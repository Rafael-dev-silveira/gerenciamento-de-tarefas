Gerenciador de lista de tarefas
=

Começamos criando a função "adicionar tarefa", que tem como objetivo adicionar tarefas à lista. Para isso, utilizamos uma lista vazia chamada "tarefas" e o método "append" para adicionar as tarefas à lista. 

Cada tarefa é armazenada em um dicionário com as chaves "tarefa" (nome da tarefa) e "completada" (indica se a tarefa foi concluída ou não). 

Em seguida, adicionamos um print para confirmar que a tarefa foi adicionada com sucesso. No menu, adicionamos um if para a escolha 1, onde perguntamos o nome da tarefa e chamamos a função "adicionar tarefa". 

Utilizamos o elif para evitar processamento desnecessário. Ao executar o programa, podemos adicionar tarefas e visualizar a lista.

Visualizando tarefas
=

Implementamos a funcionalidade de visualizar as tarefas adicionadas. 

Criamos uma função chamada "ver tarefas" que exibe a lista de tarefas armazenada. 

Utilizamos um loop for para percorrer cada elemento da lista e exibimos o índice, o status (completada ou não) e o nome da tarefa. 

Também ajustamos o índice para começar em 1, para facilitar a compreensão do usuário.

 Atualizar tarefas
 =

 Focamos na funcionalidade de atualização da tarefa, permitindo que o usuário altere o nome da tarefa. 
 
 Para isso, criamos a função atualizar_nome_tarefa, que recebe a lista de tarefas, o índice da tarefa a ser atualizada e o novo nome da tarefa. 
 
 Implementamos também a verificação do índice da tarefa, para evitar erros ao acessar elementos inexistentes na lista.


Deletar tarefas completadas
=

Criamos uma função chamada "deletar tarefas completadas" que receberá a lista de tarefas como parâmetro. 

Dentro dessa função, usaremos um loop "for" para percorrer cada tarefa da lista e verificar se ela está marcada como completa. 

Se sim, usaremos o método "remove" para excluí-la da lista. 

Ao final, exibiremos uma mensagem de sucesso. Para testar a funcionalidade, adicionaremos algumas tarefas, marcaremos algumas como completas e, em seguida, usaremos a opção de deletar tarefas completadas para ver o resultado.








 

 
