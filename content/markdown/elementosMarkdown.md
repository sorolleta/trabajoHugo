---
title: "Markdown Extendido y Completo"
---

# Guia de Markdown

contrarás una explicación completa, desde lo básico hasta gráficos y funcionalidades avanzadas.

---

## **1. Encabezado basico**

### 1.1 Tipos de encabezados
Resultado:
# Encabezado 1
## Encabezado 2
### Encabezado 3

## **1. Markdown Básico**


Usa el símbolo `#` seguido de un espacio para definir encabezados. El numero de `#` indica el nivel del encabezado:
```markdown
# Encabezado 1
## Encabezado 2
### Encabezado 3
```
### 1.2 Fuentes de textos

~~Texto~~
**Texto**
*Texto*
**_Texto_**

### 1.3 Imagenes desde enlace web

![Logo de Markdown](https://markdown-here.com/img/icon256.png)

### 1.4 Listas oredenadas

1. Elemento 1
2. Elemento 2

### 1.5 Listas desordenadas

- Elemento 1
- Elemento 2
    - Subelemento 2.1

### 1.6 Tablas

| Encabezado 1 | Encabezado 2 |
|--------------|--------------|
| Fila 1       | Valor 1      |
| Fila 2       | Valor 2      |

## **2. Markdown para Graficos**

### 2.1 Graficos con Mermaid

graph TD;
A-->B;
A-->C;
B-->D;
C-->D;

### 2.2 Tablas de Gantt con Mermaid

gantt
title Proyecto de Ejemplo
section Tarea 1
Comenzar           :a1, 2024-11-01, 3d
Terminar           :after a1, 2d
section Tarea 2
Revisión           :2024-11-05, 1d
Finalización       :2024-11-06, 1d



## **3. Markdown Extendido**

### 3.1 Codigo

```python
def saludo(nombre):
    print(f"Hola, {nombre}")
```
### 3.2 Bloques de Cita

> Este es un bloque de cita.
>> Cita anidada.

### 3.3 Notas al Pie

Markdown es fácil de usar[^1].

[^1]: Y ampliamente adoptado.

### 3.4 Matemáticas

$E = mc^2$

### 3.5 HTML Integrado

<div style="color:blue; font-weight:bold;">Texto azul y en negrita.</div>








