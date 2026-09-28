# Questionário de Interconexão — TMCO

Aplicação web do questionário TMCO (frontend + backend Express).

## Como rodar localmente

```bash
cp .env.example .env
# edite .env com EMAIL_USER, EMAIL_PASS, EMAIL_DESTINO
npm install
npm start
```

Abra `http://localhost:10000` (ou a porta definida em `PORT`).

## Segurança

Não versione o arquivo `.env` (credenciais de e-mail / banco).
