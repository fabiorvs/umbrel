# MailHog (Umbrel App)

**SMTP:** aponte suas apps para `IP_DO_UMBREL:1025`
**UI:** aberta via Umbrel (autenticada) no card do app.

## Variáveis

- `MH_UI_BIND_ADDR`, `MH_API_BIND_ADDR`, `MH_SMTP_BIND_ADDR`: portas internas (não altere).
- Exposição do SMTP (1025) é opcional; remova `ports:` no compose se não quiser acesso externo.

## Notas

- Para ARM/amd64 usei `richarvey/mailhog:latest` (multi-arch).
- Recomenda-se fixar a imagem por digest multi-arch antes de publicar.
