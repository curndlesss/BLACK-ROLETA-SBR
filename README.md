# BLACKOUT – JoJo’s Bizarre Adventure: Steel Ball Run

Roleta temática para RP de Steel Ball Run. Funciona em um único arquivo (`index.html`), sem instalação e sem build.

## O que tem

- Roleta de **Famílias** (8 giros por jogador) e roleta de **Stands** (1 giro por jogador)
- Sorteio extra de poder para os clãs **Joestar**, **Brando** (10% de Stand) e **Zeppeli** (10% de Spin e 10% de Hamon)
- Histórico da corrida (aba **Corrida**)
- Ficha de competidor no formato Steel Ball Run (aba **Ficha**)
- Gerenciar lista: ativar, filtrar, adicionar, embaralhar, restaurar e remover o item sorteado
- Efeitos sonoros sintetizados (botão para ligar e desligar)

## Como publicar no GitHub Pages

1. Crie um repositório novo no GitHub (por exemplo, `blackout-sbr`).
2. Envie os arquivos `index.html` e `README.md` para a raiz do repositório.
3. Abra **Settings → Pages**.
4. Em **Build and deployment**, escolha **Deploy from a branch**.
5. Selecione a branch `main` e a pasta `/ (root)` e clique em **Save**.
6. Depois de alguns minutos, o link aparece nessa mesma tela, no formato `https://SEU-USUARIO.github.io/blackout-sbr/`.

## Observações

- O Tailwind CSS e as fontes (Bangers e Cinzel) são carregados da internet, então a página precisa de conexão para ficar com o visual completo.
- Os dados (histórico, giros usados e número de inscrição) ficam só no navegador de cada pessoa. Quem recarregar a página recomeça do zero.
- Para mudar chances, famílias e stands, edite as constantes no começo do `<script>` em `index.html`: `STANDS`, `FAMS`, `SUB`, `CHANCE` e `CATS`.
