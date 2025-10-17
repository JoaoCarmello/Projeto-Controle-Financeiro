<h1>DT Money</h1>
<p>Projeto de controle financeiro desenvolvido com <strong>React</strong>, <strong>TypeScript</strong> e <strong>Vite</strong>.</p>

<h2>Recursos</h2>
<ul>
  <li>Cadastro de transações (entrada e saída)</li>
  <li>Listagem e busca de transações</li>
  <li>Resumo de entradas, saídas e total</li>
  <li>Estilização com <strong>styled-components</strong></li>
  <li>Validação de formulários com <strong>React Hook Form</strong> e <strong>Zod</strong></li>
  <li>Backend simulado com <strong>JSON Server</strong></li>
</ul>

<h2>Instalação</h2>
<pre>
git clone https://github.com/seu-usuario/dt-money.git
cd dt-money
npm install
</pre>

<h2>Como rodar</h2>
<ol>
  <li>
    <strong>Inicie o backend fake (JSON Server):</strong>
    <pre>npm run dev:server</pre>
    <p>O backend será iniciado na porta <strong>3333</strong>.<br>
    Acesse <code>http://localhost:3333/transactions</code> para visualizar as transações.</p>
  </li>
  <li>
    <strong>Inicie o frontend:</strong>
    <pre>npm run dev</pre>
    <p>O frontend será iniciado na porta <strong>5173</strong> (padrão do Vite).<br>
    Acesse <a href="http://localhost:5173">http://localhost:5173</a> no navegador.</p>
  </li>
</ol>

<h2>Scripts</h2>
<ul>
  <li><code>npm run dev</code> - Inicia o frontend (porta 5173)</li>
  <li><code>npm run dev:server</code> - Inicia o JSON Server (porta 3333)</li>
  <li><code>npm run build</code> - Build de produção</li>
  <li><code>npm run lint</code> - Lint do projeto</li>
  <li><code>npm run preview</code> - Preview do build</li>
</ul>

<h2>Licença</h2>
<p>MIT</p>