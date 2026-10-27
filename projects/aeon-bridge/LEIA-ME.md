# AEON Bridge — protótipo 3D independente

## Alterações
- `index.html` da raiz: **somente um novo link** na seção AEON.
- `projects/aeon-bridge/`: nova página isolada, JavaScript e modelo GLB.
- Nenhum arquivo anterior foi alterado além do `index.html` da raiz.

## Executar
Hospede a pasta em um servidor HTTP (por exemplo `python -m http.server 8000` na raiz do site) e abra `/projects/aeon-bridge/`. A página usa módulos Three.js via CDN e requer conexão à internet.

## Escopo e limitações
A interface mostra um console 3D, controles interativos, telemetria sintética, recomendação heurística, exportação e importação JSON. Não há integração real com AEON, Forja, motor físico de propulsão, banco de dados ou comunicação entre máquinas. Para integrar esses serviços será necessário um contrato de API e testes específicos. Não use os valores como orientação operacional real.

## Navegação no portfólio
AEON Bridge e Rede AEON estão listados em `projetos-navais.html` com pontos no cargueiro. A página inicial apenas apresenta a categoria naval.
