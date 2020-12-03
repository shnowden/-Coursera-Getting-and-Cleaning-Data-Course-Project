
Getting and Cleaning Data - Course Project
==========================================

* This is the course project for the Getting and Cleaning Data Coursera course.
* The included R script, `run_analysis.R`, conducts the following:


1. Download the dataset from web if it does not already exist in the working directory.
2. Read both the train and test datasets and merge them into x(measurements), y(activity) and subject, respectively.
3. Load the data(x's) feature, activity info and extract columns named 'mean'(`-mean`) and 'standard'(`-std`).
   Also, modify column names to descriptive. (`-mean` to `Mean`, `-std` to `Std`, and remove symbols like `-`, `(`, `)`)
4. Extract data by selected columns(from step 3), and merge x, y(activity) and subject data.
   Also, replace y(activity) column to it's name by refering activity label (loaded step 3).
5. Generate 'Tidy Dataset' that consists of the average (mean) of each variable for each subject and each activity.
   The result is shown in the file `tidy_dataset.txt`.
   * Este es el proyecto del curso para el curso Obtención y limpieza de datos de Coursera.
* El script R incluido, `run_analysis.R`, realiza lo siguiente:


1. Descargue el conjunto de datos de la web si aún no existe en el directorio de trabajo.
2. Lea los conjuntos de datos del tren y de la prueba y combínelos en x (medidas), y (actividad) y sujeto, respectivamente.
3. Cargue la función de datos (x), la información de la actividad y extraiga las columnas denominadas 'mean' (`-mean`) y 'standard' (` -std`).
    Además, modifique los nombres de las columnas a descriptivos. (`-mean` a` Mean`, `-std` a` Std`, y elimine símbolos como `-`,` (`,`) `)
4. Extraiga los datos de las columnas seleccionadas (del paso 3) y combine x, y (actividad) y los datos del sujeto.
    Además, reemplace la columna y (actividad) por su nombre haciendo referencia a la etiqueta de actividad (paso 3 cargado).
5. Genere un 'Conjunto de datos ordenado' que consista en el promedio (media) de cada variable para cada tema y cada actividad.
    El resultado se muestra en el archivo `tidy_dataset.txt`.