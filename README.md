# Apuração Amapá 2026

Painel com a apuração das Eleições Gerais Estaduais 2026 (1º turno, 4/10/2026) no Amapá.
Permite filtrar a votação dos candidatos por município, zona eleitoral, local de votação e seção.

## Arquivos

- `index.html`: o painel (HTML, CSS e JavaScript num único arquivo).
- `dados_ap_2026.json`: votos por seção, gerados a partir dos arquivos do TSE.
- `.nojekyll`: faz o GitHub Pages servir os arquivos sem processamento.

## Fonte dos dados

Portal de Dados Abertos do TSE:

- Votação por seção eleitoral 2026, Amapá (`votacao_secao_2026_AP.csv`, gerado em 06/10/2026 14:03:43).
- Votação nominal por município e zona 2026, Amapá (`votacao_candidato_munzona_2026_AP.csv`), usado para nome de urna, partido, federação e situação.

Os totais por seção conferem com os totais por município e zona do TSE para todos os candidatos.

## Publicar no GitHub Pages

1. Envie estes arquivos para a raiz de um repositório.
2. Em **Settings → Pages**, escolha **Deploy from a branch**, branch `main`, pasta `/ (root)`.
3. O painel fica em `https://SEU-USUARIO.github.io/NOME-DO-REPOSITORIO/`.

O painel precisa ser aberto por um endereço web (GitHub Pages ou servidor local). Abrindo o `index.html` direto do computador, o navegador bloqueia a leitura do arquivo de dados.
