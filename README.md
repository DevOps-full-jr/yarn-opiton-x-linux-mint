# yarn-opiton-x-linux-mint

1. Acesse Seu Servidor Através do SSH
Para fazer isso, nós devemos acessar nosso servidor rodando Ubuntu 18.04. Se você estiver tendo dificuldade, confira nosso tutorial sobre PuTTY.

2. Adicione a Chave GPG
Rode o seguinte comando:

curl -sS https://dl.yarnpkg.com/debian/pubkey.gpg | sudo apt-key add -
Com o comando acima, nós adicionamos a chave GPG necessária para garantir que os pacotes baixados são autênticos.

3. Adicione o Repositório Yarn
Então, nós podemos adicionar o repositório Yarn com o seguinte comando:

echo "deb https://dl.yarnpkg.com/debian/ stable main" | sudo tee /etc/apt/sources.list.d/yarn.list
4. Atualize o Sistema e Instale o Yarn no Ubuntu
Agora, tudo que nós temos que fazer é atualizar as origens do software e instalar o Yarn (yarn install) no Ubuntu usando a ferramenta APT.

sudo apt update

sudo apt install yarn nodejs
5. Confira a Versão do Yarn
Então, para checar se a instalação foi bem sucedida, nós podemos usar o seguinte comando para verificar a versão que foi instalada:

yarn –version
Como saída, aparecerá algo como:

yarn init v1.15.2
Assim como nós podemos ver, a instalação do Yarn foi bem sucedida e nós estamos prontos para trabalhar.

#`instruções de uso:`
#Modo de operação react

# yarn init -y
 cria o packge.json

** instale as dependeincias 

#yarn add express

#yarn add -D  @types/express typescrip ts-node-dev

**ativar typescrip com o comamado 

#tsc --init

**limpe o start do tsc --init

**scrict false

"()=>{}

#*

script:{

"dev":"ts-node-dev src/app.ts"	
} 

**"dotenv'

