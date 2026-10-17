# TraceCraft — Rastros da Amazônia

Aplicativo colaborativo de rastreabilidade e valorização da produção artesanal.

**Autoria e criação:** Laize Almeida de Oliveira.

## Versão de referência

Esta publicação preserva o protótipo HTML validado da versão 59, sem reescrever seus fluxos. A página inicial é `index.html`.

## Atenção: demonstração, não produção

- Cadastro e dados são mantidos no navegador; **não há autenticação Supabase integrada**. Não use senhas reais nem informações pessoais sensíveis nesta demonstração.
- O QR Code utiliza um endereço demonstrativo `tracecraft.app/p/` que ainda não corresponde a um passaporte público hospedado.
- A publicação em GitHub Pages torna a interface acessível pela internet, mas não cria automaticamente banco de dados, rede multiusuária ou armazenamento remoto.
- Antes do uso público, integrar Supabase Auth, políticas RLS, Storage e rotas públicas seguras para peças.
- A logo e os elementos visuais permanecem incorporados no HTML original.

## Publicação

1. Enviar os arquivos desta pasta para a raiz da branch `main`.
2. Em **Settings → Pages**, configurar **Deploy from a branch**, branch `main`, pasta `/(root)` (se disponível para o plano/visibilidade do repositório).
3. Confirmar o endereço publicado antes de configurar **Authentication → URL Configuration** no Supabase.

## Segurança

Nunca enviar `service_role`, `sb_secret_*`, senhas, tokens privados ou arquivos `.env` ao repositório.
