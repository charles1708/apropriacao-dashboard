# Apropriação de Horas · Dashboard

> **Primeira vez?** Siga o [passo a passo completo](PASSO_A_PASSO.md) para configurar Supabase, GitHub e o site sem erro.

Site do dashboard de apropriação de horas (Oficina de Frota e Industrial · Mineração Taboca),
publicado pelo **GitHub Pages**. Este repositório tem **só o layout**: os dados ficam no Supabase
e só aparecem para quem faz login.

## Páginas

Visão geral · Pessoas (ranking e mapa diário) · Equipamentos (inclui visão por família, ex.: Empilhadeira) ·
Ordens · Qualidade do apontamento. Filtros por ano, mês e área.

## Configuração (uma vez)

1. Edite o `config.js` aqui no GitHub (ícone de lápis) e preencha `SUPABASE_URL` e `SUPABASE_ANON_KEY`
   (Supabase > Project Settings > API > `anon public`). Commit.
2. **Settings > Pages > Build and deployment**: Source = *Deploy from a branch*, Branch = `main` / `(root)`. Save.
3. Em 1 a 2 minutos o link aparece no topo da mesma página (`https://SEU-USUARIO.github.io/apropriacao-dashboard/`).

## Quem pode ver

No Supabase: **Authentication > Users > Add user** para cada pessoa
(e desligue *Allow new users to sign up* em Sign In / Providers).

## Mudar o layout

Edite `index.html` aqui mesmo no GitHub; o site se atualiza sozinho em 1 a 2 minutos após o commit.
A referência de apropriação (78%) fica no `config.js`.
