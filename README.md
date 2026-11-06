# Ignis Alert — site do projeto

Site estático (HTML + imagens), pronto para o GitHub Pages.

## Publicar em mariadlribeiro.github.io
1. No GitHub, crie um repositório público chamado exatamente `mariadlribeiro.github.io`.
2. Envie o `index.html` para a raiz do repositório (Add file → Upload files). As imagens já estão dentro dele; a pasta `img/` é só uma cópia de reserva.
3. Em Settings → Pages, confirme a fonte "Deploy from a branch", branch `main`, pasta `/ (root)`.
4. Em alguns minutos o site abre em https://mariadlribeiro.github.io

## Atualizar a evolução
Tudo que muda com frequência fica no início do `<script>` do `index.html`:
- `ATUALIZADO_EM`: data da última atualização.
- `DIARIO`: um item por dia de trabalho (status: feito, andamento ou planejado).
- `KTH`: notas de 0 a 4 de cada ferramenta do Guia Duas Rodas.
- `IRL`: níveis do KTH Innovation Readiness Level (hoje e meta).
- `LINKS`: links do rodapé (Figma e Notion só se você quiser torná-los públicos).
- `CONTATO`: e-mail para o botão "Quero participar" da chamada final (vazio esconde o botão).
- `SIM`: os seis retornos do simulador da IA (textos e probabilidades ilustrativas).
- `TELAS`: as telas da vitrine do protótipo (imagem, título e descrição).
- `EXPERIMENTOS`: alimenta a tabela e o gráfico de dispersão.

Os números do topo ficam no HTML, nos atributos `data-count` de cada `.kpi`.
As animações respeitam a opção do sistema de reduzir movimento.

As telas em `img/` foram exportadas do Figma em 05/11/2026. As imagens estão embutidas no `index.html`. Para trocar uma tela, peça para gerar o arquivo de novo ou mude o `src` da imagem para `img/nome.png` e envie também a pasta `img/`.
