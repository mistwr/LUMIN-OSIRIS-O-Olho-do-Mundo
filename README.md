# LUMIN OSIRIS — O Olho do Mundo

Ferramenta pública de inteligência geográfica, construída para a plataforma Lumin AI.

## Primeira versão
- Mapa mundial interativo OpenStreetMap / Leaflet
- Sismos das últimas 24 horas via USGS GeoJSON
- Meteorologia atual no centro do mapa via Open-Meteo
- Vista Portugal / Mundo, marcadores, atualização manual e interface responsiva

## Executar
```bash
npm install
npm run dev
```

## Netlify
Build: `npm run build` · Diretório: `dist`. Nenhuma chave é necessária para as fontes iniciais.

## Limitações
Esta versão é um mapa 2D (o globo 3D está planeado). Não inclui ainda câmaras, vídeos, análise LLM, alertas automáticos nem processamento de satélite. Os dados públicos podem ter atrasos. Respeitar os termos de cada fornecedor e atribuição OpenStreetMap. Não utilizar streams privados ou expostos sem autorização.

## Roadmap
1. Globo 3D e camadas geográficas avançadas
2. Catálogo de câmaras públicas portuguesas autorizadas
3. IPMA, incêndios, aviação e fontes marítimas
4. Normalização temporal/geográfica e histórico PostGIS
5. Lumin AI: pesquisa, explicações fundamentadas, alertas e voz

© Lumin AI. Código próprio; verificar licenças antes de incorporar componentes de terceiros.
