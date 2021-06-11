# API_gestao_tarefas
Repositório para documentação da API de gestão de tarefas Node.js e MongoDB
# RESTFul-API do gerenciador de tarefas
Aplicativo gerenciador de tarefas desenvolvido com NODE JS e MongoDB . Ele segue uma arquitetura de design de API RESTFul . O aplicativo envia uma notificação por e-mail no momento do registro e desativação da conta do usuário. É ricamente construído com uma técnica científica simples e práticas recomendadas no mundo do design de API .

## Características
* Enviar e-mails
* Autenticação e Segurança
* Classificação, paginação e filtragem
* Upload de avatar
* Endpoints API
* Métodos	Endpoints	Acesso	Descrição
* PUBLICAR	/Comercial	Público	Inscrever-se
* PUBLICAR	/ users / login	Público	Conecte-se
* OBTER	/ users / me	Privado	Perfil do usuário
* CORREÇÃO	/ users / me	Privado	Atualizar perfil
* PUBLICAR	/ users / me / avatar	Privado	Carregar foto do perfil
* OBTER	/ users / userID / avataar	Privado	Ver foto do perfil
* EXCLUIR	/ users / me / avatar	Privado	Excluir foto do perfil
* EXCLUIR	/ users / me	Privado	Deletar conta
* PUBLICAR	/ users / tasks	Privado	Crie uma tarefa
* OBTER	/ users / tasks / taskID	Privado	Ver uma tarefa
* OBTER	/ users / tasks	Privado	Ver todas as tarefas
* OBTER	/ usuários / tarefas? limite = 2	Privado	Limite o resultado a 2
* OBTER	/ users / tasks? sortBy = createdAt: desc	Privado	Classificar por ordem decrescente da data de criação
* OBTER	/ users / tasks? sortBy = createdAt: asc	Privado	Classificar por ordem crescente de data de criação
* OBTER	/ users / tasks? skip = 3	Privado	Resultado de paginação
* CORREÇÃO	/ users / tasks / taskID	Privado	Atualizar uma tarefa
* EXCLUIR	/ users / tasks / taskID	Privado	Apagar uma Tarefa
* PUBLICAR	/ users / logout	Privado	Sair de uma conta
* PUBLICAR	/ users / logoutall	Privado	Sair de todas as contas
* Link de domínio hospedado
API do gerenciador de tarefas

Link da coleção do carteiro
Coleção compartilhada da API do gerenciador de tarefas

Contribuindo
Você pode bifurcar o repositório e enviar solicitação de pull ou entrar em contato facilmente comigo via twitter => Kater Akeren

Vulnerabilidades de segurança
Se você descobrir uma vulnerabilidade de segurança no projeto, crie um problema. Todas as vulnerabilidades de segurança serão prontamente tratadas e apreciadas.
