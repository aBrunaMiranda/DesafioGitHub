Passos para criar a chave no git
	1. No git bash digitar: ssh-keygen -t ed25519 -C email@hotmail.com
	2. Salvar o caminho gerado para salvamento da chave
	3. Entrar no diretório e digitar: cat id da chave
	4. Copiar chave exibida no site do git
	5. Pegar o id da chave. Entrar novamente no diretório de salvamento e digitar: eval $(ssh-agent -s)
	6. Passar a chave privada para o agente: ssh-add id da chave

Para clonar codigo: git clone shh do repositorio
Para colar no git bash Shift + Insert
