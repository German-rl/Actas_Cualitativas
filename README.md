[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/German-rl/Actas_Cualitativas/blob/main/notebooks/Actas_Cualitativas.ipynb)

# 📖 Instrucciones de uso

## Requisitos

Antes de ejecutar el programa, prepare un archivo de Excel (`.xlsx`) con la lista de estudiantes.

El archivo debe contener **exactamente tres columnas**, con los siguientes nombres y en este orden:

| Nombre      | Matricula | Calificación |
| ----------- | --------- | ------------ |
| Juan Pérez  | 20230001  | 95           |
| María López | 20230002  | 82           |

> **Importante:** Los encabezados deben escribirse exactamente como se muestran:
>
> * `Nombre`
> * `Matricula`
> * `Calificación`

---

## Cómo utilizar el programa

1. Abra el notebook en **Google Colab**.
2. Ejecute las celdas en orden (botón ▶️ o **Entorno de ejecución → Ejecutar todo**).
3. Cuando el programa lo solicite, seleccione el archivo de Excel con las calificaciones.
4. Responda las preguntas que aparecerán en pantalla:

   * Fecha
   * Materia
   * Semestre
   * Grupo
   * Nombre del profesor
5. Espere mientras el sistema genera automáticamente las actas en formato PDF.

> La plantilla de las actas se descarga automáticamente desde este repositorio. No es necesario cargarla manualmente.

---

## Descargar los resultados

Una vez finalizado el proceso, se generará un archivo comprimido llamado:

**`Actas_PDF.zip`**

Para descargarlo:

1. En Google Colab, haga clic en el ícono de la **carpeta (📁)** ubicado en el panel izquierdo.
2. Busque el archivo **`Actas_PDF.zip`**.
3. Haga clic en los tres puntos (**⋮**) junto al archivo.
4. Seleccione **Download** para guardarlo en su computadora.

El archivo ZIP contendrá todas las actas generadas en formato PDF.
