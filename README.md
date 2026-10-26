# Pedidos 50 Empresas

O projeto tem duas áreas independentes:

- administrativo/index.html: painel de administração e entregas.
- pedidos/index.html: sistema de pedidos das empresas.
- index.html: página inicial para escolher uma das áreas.

Cada área tem seu próprio supabase-config.js. A recuperação de senha do painel fica em administrativo/reset-password.html. No Supabase, inclua o endereço publicado dessa página em Authentication > URL Configuration > Redirect URLs.

Os endereços antigos pedidos-50-empresas.html e reset-password.html continuam redirecionando para os novos caminhos.