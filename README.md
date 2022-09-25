## Introdução
Este é um repositório com todas as principais instalações que faço em distribuições debian. Para efeitos de registro, os comandos foram testados nas distros Ubuntu e PopOS. 

### O que é instalado no sistema?
Para estilizar o terminal, utilizo os seguintes programas:
	- Zsh, Oh My Zsh!, Zsh-autosuggestions, Powerlevel10k
Para desenvolvimento:
	- NodeJS, NPM, Yarn, VSCodium, Chrome e Docker (Engine/Compose)
E para comunicação:
	- Signal e Microsoft Teams
	
### O que fazer caso não queira algum desses programas?
Edite o arquivo que instala o programa indesejado, cada arquivo possui comentários que identificam programa o código instala. Na linha do comando de instalação do programa indesejado, adicione um '#', isso irá transformar o código em um comentário.

### Fontes MesloLGS NF
Embora não seja obrigatório, o uso da fonte é recomendado para caso vá utilizar o tema PowerLevel10k no seu terminal. Para instalar siga os seguintes passos:

Acesse a pasta '.fonts', dê um duplo-clique em cada fonte e a instale. 
Feito isso, acesse as configurações do terminal e altere a fonte para MesloLGS NF.

### Arquivo basic.sh
Aqui a pasta de fontes e o arquivo zshrc são renomeados e movidos para a Home, são passos importantes para a parte de estilização do terminal. Caso não vá mexer em seu terminal, ignore esse arquivo.

Para iniciar o básico, rode:
	chmod +x basic.sh && ./basic.sh

### zsh.sh
Instalação do zsh e do oh my zsh!
Acesse o terminal na pasta em que estão os arquivos zsh.sh e o powerlevel.sh.
Execute o seguinte comando:
	./zsh.sh

### plugins.sh
Instalação de zsh-autosuggestions e do tema powerlevel10k

Execute:
	./powerlevel.sh
Para que a instalação seja completa, reinicie o seu computador.

### development.sh
Instalação do NodeJS, NPM, Yarn, Chrome, VSCodium e Docker

Acesse o terminal na pasta em que está o arquivo development.sh .
Execute o seguinte comando:
	chmod +x development.sh && ./development.sh

### communication.sh
Signal e Microsoft Teams

No mesmo terminal que utilizou na etapa anterior, execute:
	chmod +x communication.sh && ./communication

	
