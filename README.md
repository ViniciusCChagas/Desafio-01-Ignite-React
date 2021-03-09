<div align="center"><h1>:trophy: Desafio 01 - Conceitos do React</h1></div>
<br/>
<div align="justify">
&emsp;Neste desafio aplicamos os conceitos aprendidos no primeiro módulo do <a href="https://help.rocketseat.com.br/hc/pt-br/articles/1500003228822-O-que-%C3%A9-o-Ignite-" target="_blank">Ignite</a>,
manipulamos estados de uma aplicação simples de ToDo, onde deveriamos implementar as funcionalidades de: adicionar uma nova tarefa, remover uma tarefa e marcar e desmarcar uma tarefa como concluída. <br>
&emsp;Para isso, utilizamos o Hook "useState()" aplicando o conceito de <a href="https://segredo.dev/o-que-e-imutabilidade/" target="_blank">Imutabilidade</a> e por fim utilizando o a utilizamos a biblioteca de testes <a href="https://jestjs.io/" target="_blank">Jest</a> para testarmos a aplicação.

</div>
<br/>
<br/>
<br/>
<br/>

## :notebook: Instruções para uso

### 1. Clonar repositório
Você pode clonar esse repositório utilizando o comando: <br>
`` git clone https://github.com/ViniciusCChagas/Desafio-01-Ignite-React `` <br>
ou você pode baixar o repositório como um arquivo .ZIP

### 2. Instalar as dependências
Após isso, na pasta do projeto rode o comando
```bash
$ npm install
#ou
$ yarn
```
para instalar todas as dependencias do projeto. <br>

### 3. Rodar a aplicação
Depois de instalar todas as dependencias do projeto, vamos executa-lo em modo de desenvolvimento, utilizando o comando:
```bash
$ npm run dev
# ou
$ yarn dev
```
Após isso podemos acessar o App no endereço: http://localhost:3000.

### 4. Testar a aplicação
Podemos também testar a nossa aplicação, com os comandos:
```bash
$ npm run test
# ou
$ yarn test
```
## :heavy_check_mark: Específicação dos testes

- **should be able to add a task**: Para que esse teste passe, você deve permitir que task seja criada e com isso, exibida em tela. As taks criadas devem conter os atributos seguindo o padrão da interface.

- **should not be able to add a task with an empty title**: Para que esse teste passe, antes de criar uma nova task, você deve validar se algo foi digitado no input e não permitir a criação da task caso o valor seja vazio, caso o valor digitado seja vazio, você deve impedir a criação da task.

- **should be able to remove a task**: Para que esse teste passe, você deve permitir que ao clicar no botão com ícone de uma lixeira, a task relacionada a esse botão seja removida do estado da aplicação, consequentemente sendo removida da tela.

- **should be able to check a task**: Para que esse teste passe, você deve permitir que ao clicar no checkbox ao lado da task, ela seja marcada como concluída ou não concluída de acordo com seu estado atual, alterando seu valor de `isComplete` de `false` para `true` ou ao contrário, de `true` para `false`.

## :briefcase: Ferramentas utilizadas
<li>ReactJS</li>
<li>Jest</li>
<li>TypeScript</li>


## :raised_hand: Como contribuir

- Faça um fork desse repositório;
- Cria uma branch com a sua feature: `git checkout -b minha-feature`;
- Faça commit das suas alterações: `git commit -m 'feat: Minha nova feature'`;
- Faça push para a sua branch: `git push origin minha-feature`.

---

<h4 align="center">
    Feito com ♥ por Vinícius Chagas 👋 <a href="https://www.linkedin.com/in/viniciuscchagas/" target="_blank">Acompanhe!</a>
</h4>
