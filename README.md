# Taller "Plataforma GeoNode: gestión y visualización integral de datos espaciales en web"  
**Jornadas SIG Libre 2025 – Girona, 17 de septiembre de 2025**

<img width="1585" height="894" alt="imagen" src="https://github.com/user-attachments/assets/21990ac0-3dc6-42d6-918d-60be2aa0549c" />


## Objetivo

En este taller realizaremos una demostración práctica de **GeoNode**, una plataforma *open source* para publicar, gestionar y compartir datos espaciales.  

Tras una introducción al proyecto, mostraremos cómo:  
- Cargar datos vectoriales y ráster.  
- Acceder a servicios OGC externos.  
- Editar metadatos.  
- Personalizar simbología y *popups*.  
- Editar datasets vectoriales en línea.  
- Crear mapas interactivos, paneles de mando y **GeoStories**.  
- Integrar GeoNode con QGIS mediante su complemento oficial, facilitando la visualización, edición y sincronización en tiempo real.  

Un taller práctico para descubrir las ventajas de GeoNode en proyectos colaborativos con tecnologías libres.

- **Software necesario:** GeoNode  
- **Requisitos técnicos:** Ninguno  
- **Nivel:** Introductorio  
- **Conocimientos previos:** No son necesarios  

---

## Tutores
- **Patricio Soriano** – Responsable del Área de SIG y Desarrollo de Geoinnova.  
  [@sigdeletras](https://x.com/sigdeletras) · [+info](https://geoinnova.org/perfil/patricio-soriano-castro/)  

---

## Guion del Taller
1. **Geoinnova. Área de SIG y Servicios**  
   - [Información general](https://geoinnova.org/transforma-tus-decisiones-con-mapas-con-geonode-tu-geoportal-sin-complicaciones-tecnicas-general/)  
   - [Datos técnicos y servicios avanzados](https://geoinnova.org/geonode-listo-para-produccion-despliega-tu-portal-geoespacial-con-soporte-experto/)  

2. **GeoNode**  
   - Características, arquitectura, componentes y tipos de recursos  

3. **Prácticas del taller**  
   - Acceso/Interfaz  
   - Gestión de entidades (datos, metadatos, estilos, permisos…)  
   - Consulta y edición  
   - Añadir servicios externos  
   - Creación de un mapa  
   - Creación de un panel de control  
   - Acceso desde QGIS  

4. **Introducción a la administración avanzada**  
   - Arquitectura  
   - Tipos de usuarios  
   - Django Admin  
   - Gestiones desde `manage.py`  
   - API RESTful de GeoNode  

---

## Recursos necesarios
- **Demo GeoNode**: [stable.demo.geonode.org](https://stable.demo.geonode.org/#/)  
- **Repositorio GitHub con prácticas y datos**: [taller_geonode_SIGLibre2025](https://github.com/geoinnova/taller_geonode_SIGLibre2025/)  
- **Datos de ejemplo**: [datos.zip](https://github.com/geoinnova/taller_geonode_SIGLibre2025/blob/master/datos.zip)  
- **Ejercicios resueltos**: [geonode.geoinnova.org](https://geonode.geoinnova.org/#/)  

### Ejemplo de simbología (análisis de accesibilidad)
```xml
<ColorMapEntry color="#2b83ba" quantity="1" label="Óptima (<2%)" opacity="1"/>
<ColorMapEntry color="#abdda4" quantity="2" label="Alta (2-5%)" opacity="1"/>
<ColorMapEntry color="#ffffbf" quantity="3" label="Media (5-8%)" opacity="1"/>
<ColorMapEntry color="#fdae61" quantity="4" label="Baja (8-12%)" opacity="1"/>
<ColorMapEntry color="#d7191c" quantity="5" label="Muy baja o no accesible (>12%)" opacity="1"/>
```

---

## Funcionalidades destacadas de GeoNode
- **Formatos soportados:** Shapefile, GeoPackage, GeoJSON, CSV (lon/lat), KML/KMZ, GeoTIFF, 3D Tiles, SLD, entre otros.  
- **Plugin oficial para QGIS**: [QGIS GeoNode](https://plugins.qgis.org/plugins/qgis_geonode/#plugin-details)  
- **API RESTful**: permite integración y automatización vía HTTP (GET, POST, PUT, DELETE).  

---

## Enlaces GeoNode
- [Página oficial](https://geonode.org)  
- [Documentación](https://docs.geonode.org/en/master/index.html)  
- [Repositorio](https://github.com/GeoNode/geonode)  
- [Demostración oficial](http://master.demo.geonode.org)  
- [Wiki de GeoNode](https://github.com/GeoNode/geonode/wiki)  
- [Gestión de issues](https://github.com/GeoNode/geonode-project/issues)  
- [Hoja de ruta (GeoNode Improvement Proposals)](https://github.com/GeoNode/geonode/wiki/GeoNode-Improvement-Proposals)  
