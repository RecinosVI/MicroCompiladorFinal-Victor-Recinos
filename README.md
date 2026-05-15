# MicroCompiladorFinal-Victor-Recinos
Analizador Léxico

# MicroC Compilador - Fase I y II

Proyecto desarrollado en **Python** para el curso de **Autómatas y Lenguajes (2026)**.

## Descripción

MicroC Compilador es una aplicación con interfaz gráfica desarrollada en Python que implementa un **Analizador Léxico** capaz de procesar código fuente estilo C/C++ y generar una lista de tokens.

El sistema cumple con los requisitos establecidos para la **Fase I y Fase II** del proyecto.

---

## Características Implementadas

### Fase I
✔ Generación de lista de tokens

✔ Eliminación de espacios en blanco

✔ Eliminación de tabuladores y caracteres especiales

✔ Relación de líneas de código con el análisis

✔ Identificación de lexemas simples

---

### Fase II
✔ Identificación de palabras reservadas

✔ Identificación de números enteros y reales

✔ Reconocimiento de comentarios

✔ Reconocimiento de símbolos simples y dobles

✔ Manejo de errores léxicos

---

## Tecnologías utilizadas

- Python 3
- Tkinter
- Programación Orientada a Objetos

---

## Estructura del proyecto

text
MicroC_Compilador/
│
├── main.py
│
├── frame/
│   ├── __init__.py
│   └── frm_editor.py
│
├── compilador/
│   ├── __init__.py
│   ├── analizador_lexico.py
│   └── unidades_lexicas.py
│
└── README.md
