instale as dependências 
node js
npm init
Instale venom-bot como uma dependencia do seu projeto
npm install venom-bot
Instale openai como uma dependencia do seu projeto
npm install openai
Instale dotenv como uma dependencia do seu projeto
npm install dotenv


# bot-venom-kikko
baixe o arquivo (código do programa)
abra no visual studio,
crie um arquivo e coloque o nome de  .env  

dentro dele vai ter que ficar assim:  ⇩

OPENAI_KEY=sk-otzoR9pkiur4rjxc5NDGT3BlbkFJ8rNsJdBUhzwahPfI
ORGANIZATION_ID=org-UPmsCJTOetf2aUel6TX2
BOT_NUMBER=5571986860901@c.us


você vai modificar, sempre o que tiver depois do =
exemplo logo abaixo ↡

OPENAI_KEY=sk-otzoR9pkiur4rjxc5NDGT3BlbkFJ8rNsJdzwahMg4lPfI
depois do = vc vai colocar seu key que irá precisar gerar através do link abaixo
>>> https://beta.openai.com/account/api-keys
quando abrir a pagina, vc clica em >>> Create new secret key, gera o key e copia para colar no OPENAI_KEY


ORGANIZATION_ID=org-UPmsCJTOetf2aUejl6TX2
depois do = vc vai colocar seu id que irá gerar através desse link abaixo. obs:quando for gerar, vai solicitar uma confirmação.
>>>> https://beta.openai.com/account/org-settings
quando entrar vai pedir seu numero cel para confirmar e depois vc aperta em save e copia o id para colar em ORGANIZATIO_ID



BOT_NUMBER=5571986868601@c.us  E aqui vc vai TROCAR E colocar o código da sua cidade e seu numero celular. obs: só mude os numeros e salve.

pronto! agora é só abrir um novo terminal no visual studio e digitar o comando: npm start, vai gerar um qr e vc vai ter que scanear
whatsapp, depois é só testar pedindo para alguém te mandar uma pergunta com /bot  sempre antes da pergunta ou vc mesmo pode mandar 
uma pergunta para seu zap.
