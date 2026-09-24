# Love Gestão — Protótipo

Protótipo navegável do futuro sistema de gestão da **Love Dedetização**.

## O que está demonstrado

- Dashboard executivo
- Agenda de atendimentos
- Cadastro e histórico de clientes
- Orçamentos
- Ordens de serviço
- Financeiro
- Produtos e estoque
- Equipe e permissões
- Relatórios
- Modal de criação de OS
- Layout responsivo para desktop, tablet e celular
- PWA básica (instalável pelo navegador)

> Todos os dados apresentados no protótipo são fictícios e servem apenas para demonstração visual.

## Rodar localmente

Não há dependências. Basta servir a pasta com um servidor HTTP:

```bash
python -m http.server 8080
```

Depois abra `http://localhost:8080`.

## Publicar no GitHub

```bash
git init
git add .
git commit -m "Protótipo Love Gestão"
git branch -M main
git remote add origin URL_DO_SEU_REPOSITORIO
git push -u origin main
```

## Publicar no Vercel

1. Importe o repositório do GitHub no Vercel.
2. Framework Preset: **Other**.
3. Build Command: deixe vazio.
4. Output Directory: deixe vazio.
5. Clique em Deploy.

## Próxima fase

A versão final pode evoluir para React/Next.js + Supabase, com autenticação, RLS, banco real, armazenamento de fotos, assinaturas, geração de PDF, controle de permissões, financeiro, notificações e aplicativo/PWA.
