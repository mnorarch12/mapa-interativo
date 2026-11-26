# Mapa interativo no GitHub Pages

Este projeto publica o arquivo `validation_test_map.geojson` como um mapa interativo usando Leaflet e OpenStreetMap.

## Arquivos
- `index.html`: interface do mapa, filtros e janelas de identificação.
- `validation_test_map.geojson`: os 891 pontos geográficos originais.

## Como publicar
1. Entre em https://github.com e crie um repositório novo, por exemplo `mapa-interativo`.
2. Deixe o repositório como **Public** (ou verifique as condições do seu plano/organização para Pages privado).
3. Envie `index.html` e `validation_test_map.geojson` para a raiz do repositório. Os dois arquivos precisam ficar no mesmo nível.
4. No repositório, abra **Settings → Pages**.
5. Em **Build and deployment**, selecione **Deploy from a branch**.
6. Em **Branch**, selecione `main` e a pasta `/(root)`; clique em **Save**.
7. Aguarde a publicação. O endereço será semelhante a:
   `https://SEU-USUARIO.github.io/mapa-interativo/`

## Recursos já incluídos
- 891 pontos, com agrupamento automático em diferentes níveis de zoom.
- Filtro por município e classificação.
- Pesquisa por nome, endereço ou município.
- Pop-up com os atributos disponíveis.
- Cores lidas do campo `color` do GeoJSON.

## Observações
- O mapa usa bibliotecas carregadas por CDN e os mapas-base do OpenStreetMap; é necessária conexão à internet.
- O repositório público torna o GeoJSON e seus atributos acessíveis publicamente. Verifique se os dados podem ser divulgados antes de publicar.
- O arquivo original é mantido sem alterações.
