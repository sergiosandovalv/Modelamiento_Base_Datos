![Duoc UC](https://www.duoc.cl/wp-content/uploads/2022/09/logo-0.png)

# 🧠 Modelamiento de Base de Datos

**Estudiante:** Sergio Sandoval Valenzuela  
**Profesor:** Sebastián Vásquez Basaez  
**Carrera:** Analista Programador  
**Sede:** Santiago Online  

---

## 📖 Actividad actual – Semana 9 EFT

Este repositorio contiene el desarrollo de la **Evaluación Final Transversal (EFT) de la Semana 9** de la asignatura Modelamiento de Base de Datos.

El trabajo se basa en el caso **Asociación Nacional de Fútbol Profesional (ANFP)** y tiene como objetivo diseñar, normalizar e implementar una base de datos relacional utilizando Oracle SQL Developer Data Modeler y Oracle SQL Developer.

---

## 🎯 Propósito

Desarrollar una solución de base de datos relacional, aplicando:

- Diseño del Modelo Entidad-Relación Extendido (MER-E).
- Modelamiento mediante notación Barker.
- Identificación de entidades, atributos y relaciones.
- Cardinalidades, supertipos y subtipos.
- Normalización en 1FN, 2FN y 3FN.
- Transformación al Modelo Relacional (MR).
- Creación de tablas mediante DDL.
- Claves primarias y foráneas.
- Restricciones `NOT NULL`, `UNIQUE` y `CHECK`.
- Columnas `IDENTITY`.
- Modificaciones mediante `ALTER TABLE`.
- Creación de objetos `SEQUENCE`.
- Restricciones de exclusividad mediante discriminador y triggers.
- Poblamiento de tablas mediante `INSERT`.
- Uso de `NEXTVAL`.
- Consultas `SELECT`.
- Alias, concatenaciones y cálculos matemáticos.
- Filtros mediante `WHERE`, `AND` y `LIKE`.
- Ordenamiento mediante `ORDER BY`.

---

## 🛠️ Herramientas utilizadas

- Oracle SQL Developer Data Modeler.
- Oracle SQL Developer.
- Oracle Database 21c.
- Git.
- GitHub.

---

## 📂 Archivos Semana 9 EFT

- `EFT_S9_Sergio_Sandoval.sql`
- `EFT_S9_Sergio_Sandoval.zip`
- `EFT_S9_Formato_Respuesta_Sergio_Sandoval.docx`

El archivo ZIP contiene el diseño `.dmd` y su carpeta de recursos.

El script SQL contiene:

1. Limpieza inicial de tablas y secuencias mediante `DROP`.
2. Creación de las 14 tablas del modelo relacional.
3. Definición de claves primarias y foráneas.
4. Implementación de restricciones `UNIQUE` y `CHECK`.
5. Creación de los triggers de exclusividad.
6. Creación de la secuencia `SEQ_CLUB_FUTBOL`.
7. Poblamiento de las tablas requeridas.
8. Consultas SQL correspondientes a los dos informes solicitados.

---

## 📊 Informes desarrollados

**Informe 1: Asociaciones de fútbol profesional**

Consulta de asociaciones profesionales creadas después del año 2000, ordenadas por fecha de creación descendente.

**Informe 2: Patrimonio de clubes de fútbol**

Consulta de clubes profesionales, mostrando su patrimonio en pesos chilenos y su conversión a dólares, utilizando un tipo de cambio de $955 y aplicando los filtros solicitados.

---

## ✅ Resultado

El script fue probado de forma secuencial en Oracle SQL Developer, desde las sentencias `DROP` iniciales hasta los informes finales, ejecutándose sin errores Oracle.

Se validó la creación de 14 tablas, la compilación de los dos triggers, el poblamiento de 32 registros y la ejecución correcta de ambos informes SQL.

Los modelos lógico y relacional fueron desarrollados en Oracle SQL Developer Data Modeler y el DDL generado no presentó errores ni advertencias.

---

