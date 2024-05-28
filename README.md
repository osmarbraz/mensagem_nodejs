# Programa servidor API-REST de mensagens utilizando Node.js.

- O projeto foi desenvolvido no VSCode deve ser chamado "mensagem_nodejs".
- Programa cliente está no projeto "mensagem_reactjs".
- Programa servidor cria o webservice na posta 8000.
- Implementação do serviço utilizando REST e os métodos GET e POST.
- Classe Mensagem possui duas operações: setMensagem e getMensagem.

- Dependências:    
    - express,
    - cors.

- Execução:    
   <pre><code>npm start</code></pre>
   
- Atualização:

   Caso o diretório "node_modules" tenha sido apagado basta executar o comando npm a seguir para recriar a pasta e os arquivos das dependências.
   <pre><code>npm update</code></pre> 

- Arquivos em src:
    - index.js - Programa principal com o servidor Express.
    - mensagem.js - Contêm a classe da Mensagem.
    - mensagemrecurso.js - Contêm os métodos de acesso aos recursos da mensagem.
    - servicos.js - Contêm as rotas aos métodos de acesso a mensagem.