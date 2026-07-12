# Laboratorio_UCV_Sistemas_Difusos_Becas

## Cuestionario de Análisis

1. **¿Qué diferencia existe entre lógica clásica y lógica difusa?**  
   La lógica clásica es binaria e inflexible (0 o 1, pertenece o no pertenece). La lógica difusa permite matices intermedios en un intervalo continuo [0, 1], reflejando la imprecisión del lenguaje cotidiano.

2. **¿Qué es un grado de pertenencia?**  
   Es un valor de la función de membresía acotado entre 0 y 1 que indica la intensidad o medida en la que un elemento se asocia a una categoría lingüística.

3. **¿Por qué un estudiante puede pertenecer parcialmente a dos conjuntos al mismo tiempo?**  
   Debido al diseño solapado de las funciones de pertenencia. Un promedio de 12.5 puede encontrarse en el descenso de la membresía "bajo" y en la rampa de ascenso del conjunto "medio".

4. **¿Qué representa la fuzzificación?**  
   Consiste en traducir una lectura numérica nítida captada del entorno (un promedio de 16, por ejemplo) a términos lingüísticos difusos a través de sus funciones de membresía.

5. **¿Qué representa la defuzzificación?**  
   Es la transformación matemática inversa; recolecta el área difusa activada por las reglas de inferencia y la unifica en un número claro y preciso mediante métodos geométricos como el centroide.

6. **¿Qué regla difusa considera más importante en este laboratorio?**  
   La combinación `promedio["alto"] & asistencia["alta"] -> prioridad_beca["alta"]`, ya que consolida el núcleo de excelencia académica junto con el compromiso y constancia del estudiante.

7. **¿Qué diferencia encontró entre la lógica difusa y la regla rígida?**  
   La regla rígida margina drásticamente. Alguien con un promedio de 15.9 queda descartado por completo. La lógica difusa es elástica y asigna una prioridad ponderada proporcional sin cortes abruptos.

8. **¿Qué riesgos tendría usar este sistema para asignar becas reales?**  
   El sesgo intrínseco de los desarrolladores o directivos al establecer arbitrariamente los límites y pendientes de los trapecios y triángulos de los conjuntos.

9. **¿Qué variables adicionales agregaría para mejorar el sistema?**  
   Número de hermanos/dependientes en etapa escolar, distancia en kilómetros hacia el campus universitario o enfermedades crónicas familiares diagnosticadas.

10. **¿En qué otros contextos se podría aplicar un sistema difuso?**  
    Sistemas automotrices de frenado asistido (ABS), algoritmos de control para aires acondicionados inteligentes o sistemas de triaje clínico automatizado en hospitales.

### Justificación Técnica y Ética del Reto MIT
**Técnicamente**, el modelo se vuelve robusto y multidimensional; evita sesgar el análisis a una única dimensión de rendimiento académico y permite balancear variables dispares sin romper la coherencia matemática del sistema de inferencia.  
**Éticamente**, el sistema promueve la equidad social. La equidad real consiste en ponderar las oportunidades según el contexto particular. Al incluir la situación socioeconómica, el algoritmo amortigua caídas ligeras del rendimiento causadas directamente por factores de vulnerabilidad material, haciéndolo una herramienta mucho más justa.