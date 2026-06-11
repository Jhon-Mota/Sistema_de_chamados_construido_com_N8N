# Sistema de chamados com N8N

## Descrição

O workflow no N8N consiste no recebimento do chamado por meio de um fórmulario em que o usuário insere seu nome, e-mail, seleciona o assunto do chamado (Compras, Manutenção, Nota Fiscal, Acessos e Outro (Especificar em descrição) escolhe o setor que para onde o chamado será direcionado (T.I., Comercial, Financeiro, Compras e Manutenção) e especifica o chamado no campo "Descrição" que é uma textarea. <br><br>
Logo após o preenchimento do formulário, é criada uma tarefa na plataforma ClickUP no espaço do setor destinado aquele chamado com o Motivo do chamado, descrição e data da criação do chamado na status "Aberto". <br><br>
Logo após isso é enviado um e-mail para o criador do chamado confirmando a abertura do mesmo.

<img width="1447" height="679" alt="Image" src="https://github.com/user-attachments/assets/c567ffc3-e466-4916-bd33-d61e911cc9d1" /> <br>

Espaços e status de tarefas do ClickUP. <br>
<img width="1896" height="754" alt="Image" src="https://github.com/user-attachments/assets/7f0343bb-c6e0-44d9-b597-4c798baa2d44" />
