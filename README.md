## Assistente Virtual via Texto

Este projeto demonstra formas práticas de utilizar Processamento de Linguagem Natural (PLN) para criar um assistente virtual simples, porém escalável.

### Funcionalidades principais

- **Entrada por texto**: o usuário digita comandos diretamente no notebook, tornando o sistema leve e portátil.  
- **Consulta de hora atual**: informa o horário exato no formato HH:MM:SS.  
- **Pesquisa rápida na Wikipédia**: recupera um breve resumo (até 3 frases) de qualquer tópico solicitado.  
- **Busca de vídeos no YouTube**: abre, no navegador, a página de resultados para o termo desejado.  
- **Contador de piadas de programação**: o toque final de humor, trazendo piadas “ruins” via `pyjokes`.

### Estrutura do projeto

1. **Leitura de comandos**  
   - Função `pegar_texto()` captura o texto em um `input()`.  
2. **Resposta do assistente**  
   - `responda()` processa o comando e aciona a ação correspondente (hora, busca, YouTube, piada).  
3. **Loop de interação**  
   - O notebook entra num laço até o usuário digitar “sair”, mantendo o assistente sempre disponível.

-------------------------

