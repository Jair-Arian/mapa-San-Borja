# Mapa sectorizado de San Borja

Abrir index.html en un navegador con conexión a Internet. Conserva buscador, dictado, capas, grabador, resumen, CSV y enlaces de rutas del proyecto original.

El contorno usa todos los vértices de data/AREA_SANBORJA.geojson, sin simplificar. El mapa exterior permanece visible y se puede desplazar y alejar libremente. El contorno delimita San Borja; los resultados y paradas se validan contra ese polígono exacto. Los huecos entre sectores se muestran como “Área sin sector asignado”, sin excluirlos de San Borja. En solapamientos prevalece el sector de menor número.

9 sectores y 9 subsectores. Las letras A/B/C siguen el orden de las entidades de cada GeoJSON, pues no contienen identificadores. Las medidas se conservan como referencias originales; no son áreas recalculadas tras limitar el contorno.

Los GeoJSON originales están en data/ y su copia incorporada en sanborja-data.js permite abrir el mapa sin servidor local. Las rutas usan almacenamiento separado para San Borja. Los servicios de mapas y búsqueda requieren Internet y el servicio Google conserva la configuración del proyecto original. Para compartir enlaces utilizables en otros dispositivos, el sitio debe estar alojado en una URL accesible.
