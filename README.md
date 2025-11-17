# Editor de Imágenes con Álgebra Matricial

**Fundamentos de Álgebra – Unidad III: Álgebra Lineal Aplicada**  
**Tecnológico de Software**  
**Alumno:** Luis Edwuard Chay Ascorra  
**Grupo:** 1°A  
**Fecha:** Noviembre 2025

---

## Objetivo del Proyecto
El objetivo de este proyecto es aplicar conceptos de álgebra lineal para modificar imágenes digitales representadas como matrices de píxeles.  
A través de transformaciones matemáticas como combinaciones lineales, diferencias, transposición y filtros, pude implementar efectos visuales similares a los que se usan en el procesamiento digital de imágenes.

Este proyecto me permitió experimentar cómo el álgebra lineal se utiliza en áreas como visión por computadora, efectos gráficos y análisis de imágenes.

---

## Instrucciones de Ejecución

### 1. Instalar dependencias

*npm install*

---

## 2. Completar funciones
El archivo donde resolví todos los ejercicios es:

*src/ejercicios.js*

## 3. Ejecutar las pruebas automáticas
npm test

## Pruebas Automáticas

Para ejecutarlas basta usar:

npm test

## Funciones Implementadas
> Sección 1 – Lectura y conversión de imágenes

imagenAMatriz()

matrizAImagen()

obtenerCanal()

obtenerDimensionesImagen()

> Sección 2 – Transformaciones básicas por píxel

Invertir colores

Convertir a escala de grises

Manipulación simple de valores RGB

> Sección 3 – Transformaciones geométricas

Voltear horizontal

Voltear vertical

Rotar 90° utilizando transposición y volteo

> Sección 4 – Filtros y efectos

Mezcla lineal entre dos imágenes

Filtro sepia

Detector de bordes (operador simplificado)

Cada función usa conceptos matemáticos como:

suma de matrices

combinaciones lineales

diferencias entre valores

transposición

operaciones punto a punto (element-wise)

manipulación de canales de color

Si todas las funciones están correctamente implementadas, las pruebas aparecerán en verde indicando que el trabajo está completo.
daria el *passed*
Esto permite verificar que cada ejercicio cumple con los requisitos del proyecto.

# Conclusión Personal

Este proyecto me ayudó a comprender cómo una imagen puede verse como una matriz y cómo el álgebra lineal permite transformarla mediante operaciones numéricas.
Pude aplicar de forma práctica:

transposición, diferencias y comparaciones entre píxeles, combinaciones lineales, filtros por canal, y transformaciones geométricas.

Además, fortalecí mis habilidades en JavaScript, manejo de arreglos bidimensionales y el uso de pruebas automatizadas para validar código :).

---




# Editor de Imágenes con Álgebra Matricial

**Fundamentos de Álgebra - Unidad III: Álgebra Lineal Aplicada**  
Tecnológico de Software

---

## Objetivo

Manipular imágenes PNG aplicando operaciones matriciales del álgebra lineal.

---

## Instrucciones

### 1. Clonar el repositorio
```bash
git clone https://github.com/TU-USUARIO/editor-imagenes-matricial.git
cd editor-imagenes-matricial
npm install
```

### 2. Completar los ejercicios
- Abre el archivo `src/ejercicios.js`
- Completa cada función donde dice `// TODO:`
- **NO modifiques** los archivos `utilidades.js`, `matriz.js` ni los tests

### 3. Probar tu código
```bash
npm test
```

### 4. Guardar tus cambios
```bash
git add src/ejercicios.js
git commit -m "Completar ejercicios de la sección X"
git push origin main
```

### 5. Ver tu calificación
- Ve a tu repositorio en GitHub
- Click en la pestaña **Actions**
- Tu calificación aparecerá en los resultados

---

## Sistema de Calificación

| Sección | Puntos |
|---------|--------|
| 1. Commits bien documentados | 20 pts |
| 2. README actualizado y personalizado | 25 pts |
| 3. Editor funcional | 30 pts |
| 4. Funciones bien documentadas | 25 pts |
| **TOTAL** | **100 pts** |

---

## Estructura del Proyecto

```
src/
├── ejercicios.js          ← COMPLETA ESTE ARCHIVO
├── ejercicios.test.js     ← NO MODIFICAR
├── utilidades.js          ← NO MODIFICAR (funciones auxiliares)
└── matriz.js              ← NO MODIFICAR (operaciones matriciales)

imagenes/
├── entrada/               ← Imágenes de prueba
└── salida/                ← Resultados generados

guias/
├── GUIA_ESTUDIANTES.md    ← Ayuda detallada
├── GUIA_INSTRUCTOR.md     ← Soluciones (solo instructor)
└── CONCEPTOS_ALGEBRA.md   ← Teoría de álgebra lineal
```

---

## Recursos

- **Guía Estudiantes:** `guias/GUIA_ESTUDIANTES.md`
- **Conceptos Álgebra:** `guias/CONCEPTOS_ALGEBRA.md`
- **Documentación pngjs:** [npmjs.com/package/pngjs](https://www.npmjs.com/package/pngjs)

---

## Reglas Importantes

1. ✅ Solo modifica `src/ejercicios.js`
2. ❌ No modifiques los archivos de tests
3. ❌ No modifiques `utilidades.js` ni `matriz.js`
4. ✅ Puedes hacer múltiples commits
5. ✅ Todos los tests deben pasar para obtener puntos

---

## ¿Necesitas Ayuda?

1. Lee `guias/GUIA_ESTUDIANTES.md`
2. Consulta `guias/CONCEPTOS_ALGEBRA.md`
3. Pregunta a tus compañeros
4. Contacta al profesor: jorge.pedroza@tecdesoftware.edu.mx

---

**¡Éxito en tu proyecto!**
