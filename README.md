<h1 align="center">Circuitos Eléctricos</h1>

<p align="center"><strong>Escuela Superior de Cómputo · Instituto Politécnico Nacional</strong><br>Ingeniería en Sistemas Computacionales · Tercer semestre</p>

<p align="center">
  <a href="https://www.escom.ipn.mx/htmls/oferta/mapaCurrISC2020.php"><img src="https://img.shields.io/badge/ISC-Plan_2020-6D1A42?style=flat-square" alt="ISC · Plan 2020"></a>
  <img src="https://img.shields.io/badge/Semestre-III-334155?style=flat-square" alt="Semestre III">
  <img src="https://img.shields.io/badge/Grupo-3CM1-1E5A7A?style=flat-square" alt="Grupo 3CM1">
</p>

<p align="center"><a href="#programa-de-estudios">Programa de estudios</a> &nbsp;·&nbsp; <a href="#contenido-del-repositorio">Contenido</a> &nbsp;·&nbsp; <a href="#uso-del-material">Uso del material</a> &nbsp;·&nbsp; <a href="#referencias">Referencias</a></p>

---

Ejercicios resueltos, apuntes y reportes de laboratorio sobre circuitos eléctricos. Las prácticas documentan el uso del multímetro y del osciloscopio, la ley de Ohm y las leyes de Kirchhoff.

| Acceso directo | Qué encontrarás |
|---|---|
| [Consultar la guía del parcial](03_guias/g01_primer_parcial.pdf) | Punto de entrada para repasar la teoría. |
| [Resolver redes serie-paralelo](01_ejercicios/lista_01_circuitos_serie_paralelo.pdf) | Lista de ejercicios de circuitos. |
| [Revisar las mediciones](02_practicas/) | Reportes y evidencias de las cuatro prácticas. |

## Programa de estudios

Relacionar el análisis de redes eléctricas con mediciones de laboratorio y la aplicación de leyes y teoremas.

Síntesis del [programa oficial de la unidad de aprendizaje](https://www.escom.ipn.mx/docs/oferta/uaISC2020/circuitosElectricos_ISC2020.pdf), perteneciente al **Plan ISC 2020**.

**Carga semanal:** 3 horas de teoría y 1.5 de práctica. **Créditos:** 7.5 TEPIC / 5.9 SATCA.

| Unidad | Eje de estudio | Alcance |
|:---:|---|---|
| I | Elementos y magnitudes | Componentes, variables eléctricas y fundamentos de medición. |
| II | Redes en corriente continua | Métodos de análisis y teoremas aplicados a circuitos. |
| III | Respuesta en frecuencia | Representación y análisis de circuitos en el dominio frecuencial. |

**Antecedentes académicos:** Álgebra Lineal, Análisis Vectorial y Mecánica y Electromagnetismo.

El programa describe el alcance de la asignatura. Las carpetas siguientes muestran el material efectivamente disponible en esta colección.

## Contenido del repositorio

| Carpeta | Contenido |
|---|---|
| [Ejercicios](01_ejercicios/) · `01_ejercicios` | Listas de circuitos serie-paralelo y leyes de Kirchhoff. |
| [Laboratorio](02_practicas/) · `02_practicas` | Multímetro, ley de Ohm, Kirchhoff y osciloscopio. |
| [Guías](03_guias/) · `03_guias` | Repaso del primer parcial. |
| [Apuntes](04_apuntes/) · `04_apuntes` | Cuaderno y notas de clase. |

Los números de actividad conservan la identificación de las entregas; las guías se distinguen por el prefijo `g` y las prácticas por `p` o `act`, según la materia.

## Uso del material

### Recorrido de laboratorio

| Práctica | Qué consultar |
|---|---|
| [P01 · Multímetro](02_practicas/p01_uso_del_multimetro/) | Instrumento, magnitudes medidas y registro de resultados. |
| [P02 · Ley de Ohm](02_practicas/p02_ley_de_ohm/) | Relación entre tensión, corriente y resistencia. |
| [P03 · Kirchhoff](02_practicas/p03_leyes_de_kirchhoff/) | Comparación del análisis de nodos y mallas con las mediciones. |
| [P04 · Osciloscopio](02_practicas/p04_manejo_del_osciloscopio/) | Observación de señales y lectura de sus parámetros. |

Para estudiar una práctica, lee el reporte, reproduce el cálculo y contrástalo con las evidencias de medición. Anota unidades, polaridades y valores de los componentes para que la comparación tenga sentido.

Los PDF pueden consultarse directamente en GitHub o descargarse. Los archivos editables y las evidencias se encuentran junto al reporte de su práctica. La relación con [Ecuaciones Diferenciales](https://github.com/EmilioNoyola/Ecuaciones_Diferenciales_3CM3_NGED) ayuda a continuar hacia el estudio de sistemas dinámicos.

<details>
<summary><strong>Clonar el repositorio</strong></summary>

```powershell
git clone https://github.com/EmilioNoyola/Circuitos_Electricos_3CM1_ATLG_HEY_HX_NGED.git circuitos_electricos
cd circuitos_electricos
```

</details>

## Referencias

- [Programa oficial de Circuitos Eléctricos — PDF](https://www.escom.ipn.mx/docs/oferta/uaISC2020/circuitosElectricos_ISC2020.pdf): unidades, carga académica, evaluación y bibliografía institucional.
- [Catálogo de unidades de aprendizaje de ISC 2020](https://www.escom.ipn.mx/htmls/oferta/mapaCurrISC2020.php): programas oficiales publicados por ESCOM.
- [Mapa curricular de ISC 2020 — PDF](https://www.escom.ipn.mx/docs/oferta/mapaCurricularISC2020.pdf): ubicación de la materia en la carrera.

---

**Repositorios relacionados:** [Ecuaciones Diferenciales](https://github.com/EmilioNoyola/Ecuaciones_Diferenciales_3CM3_NGED) · [Fundamentos de Diseño Digital](https://github.com/EmilioNoyola/Fundamentos_de_Diseno_Digital_3CM1_ATLG_HX_NGED).

Colección académica de [Emilio Noyola](https://github.com/EmilioNoyola). La autoría de cada entrega se indica en su portada o en el código correspondiente.
