# Aterrizajes y despegues de ANAC, 2023 a 2026 (corte del 7/10/2026)

Copia congelada de los cuatro archivos anuales que publica la Administración Nacional de Aviación Civil (ANAC), usados en el Trabajo Práctico Integrador de Aprendizaje Automático (UGR, 2026), Grupo 20.

ANAC reemplaza el archivo del año en curso todos los meses y corrige los dos últimos meses publicados. Esta copia fija los datos tal como estaban el **7 de octubre de 2026**, para que los resultados del trabajo se puedan reproducir. En ese corte, julio y agosto de 2026 figuraban como provisorios.

## Archivos

Cada archivo es el CSV original sin modificar, comprimido con gzip. pandas lo lee directamente: `pd.read_csv(ruta, sep=";")`.

| Archivo | Registros | MD5 del CSV descomprimido |
| --- | --- | --- |
| `2023.csv.gz` | 557.152 | `4341a7ee5278988f7ecaa5fba40e461c` |
| `2024.csv.gz` | 578.602 | `c68cfaa3ae22de1e45f56d5cc87090ff` |
| `2025.csv.gz` | 597.784 | `c6fed530e1d326322a732cd7c7d85eca` |
| `2026.csv.gz` | 371.802 | `b6a08e63fb6da8b78750b2595f7c4155` |

El archivo de 2026 llega hasta el 31 de agosto de 2026.

## Fuente y licencia

Fuente: ANAC, *Aterrizajes y despegues procesados por la Administración Nacional de Aviación Civil*, Portal de Datos Abiertos del Ministerio de Transporte (datos.transporte.gob.ar).

Los datos se redistribuyen bajo la Licencia de Datos Abiertos de la República Argentina (Decreto 117/2016), que permite copiarlos y distribuirlos citando a ANAC como fuente.
