# WebGIS com Python, Streamlit e Folium

## Como rodar o projeto

1. Instale as dependências:
   ```
   pip install -r requirements.txt
   ```

2. Certifique-se de que o arquivo `area_do_imovel.geojson` está na pasta `Shapefile`.

3. Execute o aplicativo:
   ```
   streamlit run app.py
   ```

4. O mapa será aberto no navegador. Você pode alternar entre 3 mapas de fundo e exibir/ocultar o GeoJSON.

- O arquivo GeoJSON deve estar na pasta `Shapefile`.
- O zoom inicial foca na área do GeoJSON. 