# Oportunidades inmobiliarias en Baja California

Proyecto de consultoría de datos que busca zonas de Baja California donde la actividad turística y comercial (restaurantes, hoteles, vinícolas, boutiques) crece más rápido que la oferta de vivienda ejecutiva y oficinas de categoría media-alta.

**Alumna:** Alejandra Buelna Méndez
**Grupo:** 371
**Materia:** Patrones de comportamiento de datos
**Universidad:** Universidad Autónoma de Baja California (UABC)

## Cliente y pregunta de negocio

**Cliente:** inversionista privado del sector inmobiliario.

**Pregunta:** ¿En qué municipios o zonas de Baja California la actividad turística y comercial está creciendo más rápido que la oferta de vivienda residencial ejecutiva y de oficinas de categoría media-alta?

## Datos

| Tabla | Origen | Uso |
|---|---|---|
| `denue_inegi_oficial` | DENUE (INEGI), PostgreSQL | Negocios por giro SCIAN, municipio, localidad y año de alta |
| Precios de inmuebles | Por confirmar | Confirmar escasez de oferta |
| Noticias | Por confirmar | Detectar proyectos anunciados |
| Catálogos (municipios, SCIAN) | Por confirmar | Unir tablas por clave |

## Avance

- [x] Definición del cliente, objetivo y pregunta de negocio
- [x] Revisión de la estructura de `denue_inegi_oficial` (42 columnas)
- [x] Selección de columnas y clasificación de giros SCIAN
- [x] Consultas SQL de calidad de datos y de análisis (`consultas_analisis_bc.sql`)
- [x] Informe redactado hasta la sección 4 (fuentes de información)
- [ ] Confirmar tablas de precios, noticias y catálogos
- [ ] Ejecutar consultas y obtener resultados
- [ ] Hallazgos, calidad de datos, recomendación y conclusiones

## Archivos

- `consultas_analisis_bc.sql`: consultas en PostgreSQL. Los bloques de precios y noticias usan nombres de tabla supuestos que se ajustarán al confirmar la base.
