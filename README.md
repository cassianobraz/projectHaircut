#Hairday

## Descrição
O <strong>hairday</strong> é um projeto desenvolvido com javaScript. O projeto utiliza várias tecnologias e funcionalidades avançadas do webpack, incluindo style-loader, html-webpack-plugin, copy-,webpack-plugin, css-loader, babel e biome como linter. Além disso, os dados são armazenados e recuperados com o json-server.

## Tecnologias Utilizadas
- webpack: ficou responsavel pelo build do projeto aliado ao babel para garantir o build e funcionamento da aplicação.
- json-server: API REST ficou responsavel por criar e deletar registros de agendamentos.
  
## Funcionalidades
- Escolher dias para agendar.
- Exibir dias agendados com nome dos clientes.
- Bloquei de data e dias no passado não poderam ser agendados.

## Algumas imagens: 
![image](https://github.com/user-attachments/assets/352beb08-f2eb-44d4-9ae5-5c3b6bb0873c)

### Como Executar o Projeto
```sh
git clone https://github.com/cassianobraz/projectHaircut.git
```
### Navegue até o diretório do projeto
```sh
cd hairday
```
### Instale as dependências
```sh
pnpm i
```
### Inicie o servidor backend
```sh
pnpm run server
```
### Inicie o servidor frontend
```sh
pnpm dev
```
