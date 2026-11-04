# Twitchterino

App para Windows que acompanha os canais parceiros do PokeIdle na Twitch. Ele mostra o saldo de pontos de cada canal com o preço real dos bônus, pega o baú de +50 por você e junta o chat de todos os canais num só lugar.

**Download:** https://viinnisantoos.github.io/twitchterino/

## Recursos

- **Preço real de cada canal:** o app lê a loja de cada streamer (bônus de 1 h, 3 h, 5 h e 10 h) e avisa quando um preço muda.
- **Foco em bônus:** as lives abertas vão para os canais mais perto do próximo bônus. Canais em que você é sub vêm primeiro.
- **Baú de +50 automático:** o app clica no baú de bônus quando ele aparece. Dá para desligar.
- **Bônus ativos com cronômetro:** compras feitas no app entram sozinhas. Um aviso aparece 5 min antes de acabar.
- **Lista lateral:** foto de cada streamer com um anel de progresso até o próximo bônus, grupos (Fixados, Ao vivo, Offline) e busca (Ctrl+K).
- **Teste de várias lives:** mede com a sua conta em quantas lives os pontos sobem ao mesmo tempo.
- **Chat de todos os canais:** emotes, destaque de menção e aviso de sorteio.
- **Relatório da semana:** salva uma imagem pronta para postar.
- **Modo antes de dormir:** opcional, abre as lojas uma de cada vez.
- **Modo leve:** lives ocultas em 160p, sem som e sem anúncios. O app fica na bandeja e pode iniciar com o Windows.

## O que o app não faz

- Não usa mais de uma conta ao mesmo tempo.
- Não compra bônus sozinho. A compra é sempre feita por você.
- Não guarda sua senha. O login é feito na página oficial da Twitch, e a sessão fica só no seu PC.

## Desenvolvimento

```bash
npm ci
npm start
npm run dist
```

- `npm start` roda o app.
- `npm run dist` gera o instalador e a versão portátil em `dist/`.

As atualizações automáticas chegam pelo GitHub Releases.

Projeto independente, sem ligação com a Twitch ou o PokeIdle. Licença MIT.
