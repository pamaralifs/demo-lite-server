# demo-lite-server
Projeto da demonstrar o servidor lite-server baseado no Node.
https://github.com/johnpapa/lite-server

# Passo da criação da demo
## Criação do manifesto
npm init (Para criar o package.json)

## Instalação do pacote lite-server
npm install lite-server --save-dev (Para instalar o pacote lite-server apenas em desenvolvimento, caso contrário seria --save)

## Alteração do arquivo package.json em "scripts"
Adicionar o valor para "start", ou seja, "start":"npm run lite"
Adicionar "lite":"lite-server" (na linha abaixo do identificador "test")

## Testar
Criar o arquivo index.html
Inicializar o servidor com: npm run lite
