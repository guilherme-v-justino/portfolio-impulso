# Impulso Gestão

O projeto nasceu da necessidade de concentrar agenda, cadastros, evolução clínica, pacotes, recebimentos e documentos de uma clínica de fisioterapia veterinária. A equipe precisava consultar e alterar a agenda pelo celular e manter a operação principal no Windows.

## Como foi construído

O aplicativo desktop usa Python, Flask e SQLite, com interface web servida localmente. A agenda mobile usa JavaScript, Firebase Authentication e Firestore. A sincronização é opcional. A parte online guarda os dados operacionais da agenda, enquanto prontuário, documentos e registros financeiros ficam na base local.

O agendamento precisa reservar o horário do profissional e a sessão disponível no pacote. A confirmação agrupa essas alterações em uma transação e registra a operação para evitar duplicidade em reenvios. Quando a conexão cai, a interface permite consultar a última cópia sincronizada e revalida o pedido antes de confirmar. Em agendamentos recorrentes, o resultado é apresentado por ocorrência para permitir retomar as pendentes.

## Validação

A sincronização Windows ↔ celular foi testada nos dois sentidos, incluindo acesso em um segundo celular e recuperação após reiniciar o servidor local. O aplicativo possui um modo de demonstração separado da base usada na clínica.

[Voltar ao portfólio](README.md)
