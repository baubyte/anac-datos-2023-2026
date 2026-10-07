# Aterrizajes y despegues de ANAC, 2023 a 2026

Datos usados en el Trabajo Práctico Integrador de Aprendizaje Automático (UGR, 2026), Grupo 20.

## Archivos

| Archivo | Contenido |
| --- | --- |
| `2023.csv.gz` a `2026.csv.gz` | Archivos originales de ANAC descargados el 7 de octubre de 2026, sin modificar y comprimidos con gzip. El de 2026 llega hasta el 31 de agosto. |
| `anac_demanda_aeropuertos_2023_2026.csv` | Dataset limpio: una fila por aeropuerto y día a pronosticar, con las variables del pasado, el calendario y las dos variables objetivo (pasajeros y operaciones). |

pandas lee los archivos comprimidos directamente: `pd.read_csv(ruta, sep=";")`.

## Fuente y licencia

Fuente: ANAC, *Aterrizajes y despegues procesados por la Administración Nacional de Aviación Civil*, Portal de Datos Abiertos del Ministerio de Transporte (datos.transporte.gob.ar).

Los datos se redistribuyen bajo la Licencia de Datos Abiertos de la República Argentina (Decreto 117/2016), que permite copiarlos y distribuirlos citando a ANAC como fuente.
