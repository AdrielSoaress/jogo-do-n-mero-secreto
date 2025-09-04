# Jogo do Número Secreto 🎲

Um jogo simples em JavaScript onde o usuário tenta adivinhar um número secreto entre 1 e 10.

## Funcionalidades

- Geração aleatória de um número secreto de 1 a 10.
- Contador de tentativas.
- Indicação se o número secreto é maior ou menor que o chute.
- Evita que o mesmo número seja gerado novamente até que todos os números sejam usados.
- Botão para reiniciar o jogo.

## Tecnologias

- HTML
- CSS (opcional)
- JavaScript

## Como jogar

1. Abra o arquivo `index.html` no seu navegador.
2. Digite um número entre 1 e 10 no campo de entrada.
3. Clique em "Chutar" (ou pressione Enter se implementar essa funcionalidade).
4. Veja se acertou ou se precisa tentar novamente.
5. Quando acertar, clique em "Reiniciar" para jogar novamente.

## Estrutura do Código

- `index.html` → Contém a estrutura do jogo.
- `style.css` → Estilização opcional.
- `script.js` → Lógica do jogo:
  - Função `gerarNumeroAleatorio()` → cria um número aleatório único.
  - Função `verificarChute()` → verifica se o chute está correto.
  - Função `exibirTextoNaTela()` → atualiza o conteúdo do HTML.
  - Função `limparCampo()` → limpa o input.
  - Função `reiniciarJogo()` → reinicia o jogo.

## Como contribuir

1. Faça um fork do projeto.
2. Crie uma branch com sua feature: `git checkout -b minha-feature`.
3. Commit suas alterações: `git commit -m 'Adicionei algo legal'`.
4. Push para a branch: `git push origin minha-feature`.
5. Abra um Pull Request.

## Autor

- Adriel Santos Soares 

