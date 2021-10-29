# Analisis de datos exploratorios
Título: QTL-SRS

# Autor
Dr. Marcos Mancilla

# Contacto
<mmancilla@adldiagnostic.cl>

# Resumen del problema a resolver
La piscirickettsiosis o SRS es una enfermedad infecciosa que afecta salmónidos en fase de engorda. Entre las medidas de control y prevención disponibles están el uso de vacunas, antibióticos para tratamiento, aditivos en dietas y selección de peces resistentes. Para esta última, la selección se basa en la identificación de marcadores genéticos (loci) relacionados con el fenotipo deseado, los cuales pueden presentar un grado de heredabilidad variable. Esto se conoce como QTL (Quantitative Trait Loci). Se busca determinar si alguno de los grupos de peces salmón Coho, seleccionados por distintos QTL de resistencia a SRS, presentan una disminución en las pérdidas asociadas a mortalidades SRS. Por lo tanto, la variable predictora será el grupo o subgrupo de pez (genotipo), mientras que la variable respuesta será la mortalidad asociada a SRS.

# Descripción detallada de los datos
El set de datos a analizar contiene 12825 observaciones. Recoge información productiva y sanitaria de 4 centros de engorda, recolectada en una ventana de tiempo que se extendió por varios meses durante 2019, previo a la cosecha. Los centros contienen peces de la especie salmón Coho provienientes de distintos orígenes. Dichos peces se destinaron a distintas jaulas (Unidad) donde tuvo lugar la engorda. Algunos de estos individuos se seleccionaron por la presencia de marcadores o QTL de resistencia para SRS (Subgrupo). Cada observación contiene valores para la variable de interés Mortalidad por SRS (recuento n° de individuos muertos), Biomasa asociada a dicha mortalidad (kg), así como el n° de peces remanente en la jaula y Biomasa viva (kg), todas ellas variables continuas. 
Adicionalmente, el dataset incluye datos de alimentación (kg de alimento) y temperatura del agua (°C), así como n° de individuos cosechados y biomasa cosechada (kg).
