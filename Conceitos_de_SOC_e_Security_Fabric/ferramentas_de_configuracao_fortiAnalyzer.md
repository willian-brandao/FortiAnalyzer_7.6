# Ferramentas de Configuração do FortiAnalyzer

<img width="690" height="396" alt="image" src="https://github.com/user-attachments/assets/0aea74d1-2f7b-4c82-9b26-e8a0a46b0ad6" />

É possível utilizar GUI ou CLI para configurar e gerenciar o FortiAnalyzer. Pode se usar as ferramentas localmente por conexão direta com o FortiAnalyzer, ou remotamente, baseado em suas configurações. Pode-se permitir ou negar baseado em endereços IP.

Quando é usado a CLI, pode se rodar comandos através do widget cli console, disponível na GUI dashboard, ou através de um terminal de emulação. Usando o putty requer conecção telnet, ssh ou local.

Os recursos do FortiAnalyzer disponíveis na GUI e CLI dependem do perfil que está configurado como o administrador do modo de operação do FortiAnalyzer. Por exemplo, no modo coletor, a GUI não inclui FortiView, Reports ou Incidentes e Eventos. Adicionalmente, se a autenticação for no modo usuário padrão ou usuário restrito, não é habilitado o modo de acesso a todos os privilégios. Esses privilégios são reservados para super usuário. A CLI tambpém inclui algumas configurações que não são habilitadas através da GUI.
Qualquer configuração que for feita usando a GUI e CLI tem efeito imediato uma vez aplicadas nas configurações, requerindo reset do FortiAnalyzer ou interrompendo os serviços. 
