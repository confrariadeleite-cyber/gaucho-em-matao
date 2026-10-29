# Gaúcho em Matão — Site

Site estático em um único arquivo: `index.html`. Não precisa de build.

## Antes de publicar
1. Abra `index.html` e procure por `const CONFIG=`.
2. Preencha `whatsapp` com o número só com dígitos, incluindo país e DDD (exemplo: `5516999999999`).
3. Preencha `responsavel` com nome ou CNPJ do responsável pelos dados (LGPD).

## Publicar
1. Suba `index.html` e este `README.md` em um repositório no GitHub.
2. Na Vercel, importe o repositório: Framework Preset `Other`, sem comando de build e sem diretório de saída.
3. Clique em Deploy. A cada alteração no GitHub, a Vercel publica de novo.

## Pendências
- Os cadastros do formulário não são salvos (não há servidor). Hoje o envio é pelo WhatsApp.
- Confirmar com a Vitta o uso das imagens, do logotipo e do slogan, além de metragem, preço e prazo do Duo Sinharinha.
- Painel administrativo: depende de banco de dados e backend (ex.: Supabase).
