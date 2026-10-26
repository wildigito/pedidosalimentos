# Pedidos 50 Empresas

- `reset-password.html`: pagina aberta pelo link de recuperacao enviado por e-mail.

- `index.html`: painel administrativo, acessível por contas com perfil `admin` ou `entregador`.
- `pedidos-50-empresas.html`: sistema de pedidos para gerentes.
- `supabase-config.js`: URL do Supabase e chave publishable do navegador.

Mantenha os dois arquivos HTML no mesmo diretório para que o painel possa abrir o sistema de pedidos.
Para recuperar a senha, inclua o endereco desta pagina em Authentication > URL Configuration > Redirect URLs no Supabase.
O SQL e a Edge Function do Supabase são configurados no Supabase e não fazem parte dos arquivos públicos do site.
