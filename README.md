# Corrientes y remolinos

- **Título**: Evolución de los remolinos en la zona de confluencia Brasil-Malvinas
- **Participantes**: Harold Alberto	Fenco Chavesta, Damián 	Pérez Pérez, Fredy Guarachi 
- **Mentor**: [Charles Troupin](https://github.com/ctroupin/)
- **breve descripción**: El objetivo de este proyecto es examinar las propiedades de los remolinos en la zona de confluencia Brasil-Malvinas a partir de datos de altimetría y analizar si ha habido cambios en un periodo de 20-30 años.
- **Lenguaje**: Python

![image](https://github.com/user-attachments/assets/4f65e7e2-0c92-45d6-8da1-af7f79e2d54e)


## Datos

La fuente principal de datos es el producto `SEALEVEL_GLO_PHY_L4_MY_008_047`: "Global Ocean Gridded L 4 Sea Surface Heights And Derived Variables Reprocessed 1993 Ongoing", DOI: [10.48670/moi-00148](https://doi.org/10.48670/moi-00148).

**Cobertura espacial:** global        
**Cobertura temporal:** desde 1 de enero 1993      
**Resolución espacial:** 0.125° × 0.125°              
**Nivel de procesado:** nivel 4       

## Herramientas

El paquete [`py-eddy-tracker`](https://github.com/AntSimi/py-eddy-tracker) en Python, que permite la detección de remolinos y su seguimiento a partir de datos de altimetría o de salidas de modelos numéricos.

> Mason, E., A. Pascual, and J. C. McWilliams (2014), A new sea surface height based code for oceanic mesoscale eddy tracking, _J. Atmos. Oceanic Technol._, **31(5)**, 1181–1188, doi: [10.1175/JTECH-D-14-00019.1](https://doi.org/10.1175/JTECH-D-14-00019.1). 

## Zona de interés

El trabajo se centra sobre la zona de confluencia Brasil-Malvinas, con coordenadas (aprox.)   60.76°W - 37.96°W, 29.70°S - 42.23°S.

![Screenshot from 2024-11-26 22-22-57](https://github.com/user-attachments/assets/fde94384-d2a0-4f64-84cb-d2e801cf0c33)






