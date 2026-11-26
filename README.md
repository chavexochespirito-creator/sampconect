# Bot Status SA:MP / open.mp (Estilo Stars Games)

Bot adaptado do motor UDP do `open.monitor` com visual idêntico ao card de status do Discord (Embed verde/vermelho, blocos de código para **Jogadores**, **Status** e **IP**, rodapé atualizado a cada **30s** e botões **BAIXAR MOBILE** e **BAIXAR PC**).

## Como subir no GitHub pelo Celular e rodar no Render

1. **Suba os arquivos desta pasta para o seu repositório GitHub** (`index.js` ou `package.json` na raiz do repositório).
2. **No Render (Build & Start Command):**
   - **Build Command:** `npm install && npm run build`
   - **Start Command:** `npm start`
3. **Environment Variables no Render:**
   - `TOKEN`: Token do seu bot no Discord
   - `CLIENT_ID`: ID do aplicativo do bot SEUTOKEN
   - `MONGO_URI`: Sua URL do MongoDB Atlas
4. **No Discord:**
   - Digite `/painel` em qualquer canal (apenas Administradores veem).
   - Toque em **Editar IP e Nome**, escolha o canal de texto no menu e clique em **Postar / Atualizar Agora**.
   - 
