# Plantilla
Este repositorio será usado para el proyecto de Formulario Automatizado.
# Proyecto: DOCS-FILL-AUTO (Versión 2)

El objetivo principal de este proyecto es automatizar completamente el proceso de llenado de los documentos de cierre de proyectos de telecomunicaciones.

En esencia, la aplicación debe:

Leer y entender las plantillas de documentos vacías.
Extraer automáticamente toda la información necesaria de diversas fuentes, como PDFs técnicos (CDs), y datos de etiquetas en fotografías de equipos.
Usar ejemplos de documentos ya completados como guía para saber exactamente en qué celda o lugar va cada dato.
Rellenar las plantillas con la información extraída y las fotos correspondientes.
Generar los documentos finales y guardarlos en una carpeta designada, listos para ser entregados.

## Objetivo del Proyecto

Automatizar el llenado de **todos** los documentos de cierre para cualquier proyecto de telecomunicaciones, usando una estructura de carpetas organizada. El sistema es capaz de tomar datos de PDFs, buscar los ejemplos correspondientes, y rellenar las plantillas con la información y fotos correctas.

## Estructura de Carpetas Clave

*   `LAKE VERMILLION SITE INFO/`: **(Fuente de Datos)** Contiene los PDFs con toda la información técnica del proyecto actual (CDs, RFDS, etc.).
*   `DOCUMENTOS_PARA_LLENAR/`: **(Plantillas)** Contiene los archivos de Excel vacíos que se deben rellenar.
*   `EJEMPLOS_PROFESIONALES/`: **(Guía/Ejemplos)** Contiene los mismos archivos de Excel pero ya llenados correctamente. El script los usa como referencia para saber dónde va cada dato.
*   `FOTOS_DECOMISADOS/`: **(Fotos de Equipos)** Contiene las fotos de todos los equipos que se han retirado del sitio para el proyecto actual.
*   `CLOSEOUT_PHOTOS/`: **(Fotos de Cierre)** Contiene las fotos generales para el documento específico de "Crown Closeout Package".

## Flujo de Trabajo del Agente

1.  **Analizar Plantillas:** El agente revisará cada archivo en `DOCUMENTOS_PARA_LLENAR`.
2.  **Buscar Ejemplo:** Para cada plantilla, buscará su contraparte correspondiente en `EJEMPLOS_PROFESIONALES`.
3.  **Extraer Datos:** Leerá los PDFs en `LAKE VERMILLION SITE INFO` para obtener los datos necesarios.
4.  **Mapear y Rellenar:** Comparando la plantilla vacía con el ejemplo lleno, el agente determinará en qué celdas debe escribir los datos extraídos.
5.  **Insertar Fotos:** El agente tomará las fotos de `FOTOS_DECOMISADOS` y `CLOSEOUT_PHOTOS` y las insertará en los lugares correctos según los ejemplos.
6.  **Guardar Resultado:** Los documentos completados se guardarán en una nueva carpeta llamada `DOCUMENTOS_COMPLETADOS`.
7.  **Celdas* se utilizaran ce;das A para assets tags y Celda B para seria; # estp se llevara a cabo en hoja # 5de izquierda a derecha


nuevas instrucciones para forma de AMF form en pestana # 5
 columna A ingresar Assts tags de equipos decomiados HAY UNA CARPETA CON NOMBRE "FOTOS-DECOMISADOS" FOTOS DE EQUIPOS   es una etiqueta color naranja con un codigo de barra ejemplo ATT22937758 y numeros todo el tiempo
(Dato 1)

columna B ingresar S/N (s) AS203902244 lo puedes encontrar en una etiqueta color blanca y siempre de esA manera
 
COLUMNA f (Dato 2)(1P)(1P)473966A.101  EN ESTA MISMA ETIQUE econtraras informacion para 4 columnas  QUE SON LAS SIGUIENTES: B, E, F POR ULTIMO G.  lO mas importante es el S/N columna en  B, (Dato 3) COLUMNA E:manufacturer:  ANTENNAS, PAWERWAVE, KMW, COMSCOPE, TMA
En columna E y en esa misma etiqueta encontraras (Dato 4)  
en columna G (part descripcion) puede ser las siguiente letras O (MODELOS DE RRH NO ES NECESARIO QUE AGREGUES RRH SOLO LOS MODELOS= AHCA, AHBCB, AHFIB, AHLBA,) 
COLUMNA C QTY = 1 UNA LINEA POR CADA EQUIPO.
COLUMNA D= ITEM NUMBER (PREFERED IF AVAILEBLE)=N/A
COLUMNA H= ASSET QUALITY= USED
COLUMNA I= TOE TAG= VACIO NO ESCRIBIR NADA
COLUMNA J= REASON FOR ASSET/PART RETURND= DECOMMISION
COLUMNA K= FROM LOCATION NUMBER (ORACLES) INFORMACION SUBSTRAIDA DEL CD SIEMPRE SON 8 DIGITOS Y COMIENZAN CON 10117556 (SOLO EJEMPLO)
COLUMNA L= FROM SITE NAME= INFORMACION SUBSTRAIDA DEL CD HAY UNA CARPETA EN EL PROYECTO NOMBRE= DOCUMENTOS MARCADOS AHI HAY EJEMPLOS
COLUMNA M= DEJAR EN BLANCO
COLUMNA N= DEJAR EN BLANC0
COLUMNA O= DEJAR EN BLANCO
COLUMNA P= TO SITE NAME= MINIAPOLIS 
COLUMNA Q= PROJECT NUMBER INFORMACION SUBSTRAIDA DEL CD:  DE DONDE DICE IWM #: WSUMW0042292 (HAY VARIOS PERO SOLO SE NECESITA EL PRIMERO

ALGO MUY IMPORTANTE NO MODIFICAR ESTRUCTURA NI MONIFICAR NOMBRES y siempre dejar en orden la forma las lineas todas de un solo tamano


