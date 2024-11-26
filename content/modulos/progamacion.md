---
title: "Introducción a Java"
date: 2024-11-26
---

# Introducción a Java

Java es uno de los lenguajes de programación más populares y usados en todo el mundo. Es un lenguaje que se utiliza tanto para aplicaciones de escritorio como para aplicaciones web, móviles y hasta juegos. Una de las características más destacadas de Java es que **es multiplataforma**, es decir, el mismo código puede ejecutarse en diferentes sistemas operativos sin modificarlo.

## ¿Qué es Java?

Java es un lenguaje de programación orientado a objetos, lo que significa que todo en Java es tratado como un "objeto", lo que ayuda a organizar y estructurar mejor los programas. Este lenguaje fue diseñado para ser fácil de aprender, pero también muy potente, y es usado en muchos ámbitos como desarrollo web, aplicaciones móviles (especialmente en Android), y software empresarial.

En Java, se escriben programas en archivos con extensión `.java`, los cuales luego se compilan en bytecode que puede ser ejecutado en cualquier dispositivo que tenga instalada la Java Virtual Machine (JVM).

## Sintaxis básica de Java

La sintaxis de Java es similar a otros lenguajes como C y C++, pero es más sencilla en muchos aspectos. Vamos a ver un ejemplo básico de un programa en Java:

```java
public class HolaMundo {
    public static void main(String[] args) {
        System.out.println("¡Hola Mundo!");
    }
}
```

public class Variables {
    public static void main(String[] args) {
        int edad = 25;               // Entero (número)
        String nombre = "Yeray";      // Cadena de texto
        double altura = 1.75;         // Número con decimales
        boolean esEstudiante = true;  // Verdadero o falso
        
        System.out.println("Nombre: " + nombre);
        System.out.println("Edad: " + edad);
        System.out.println("Altura: " + altura);
        System.out.println("¿Es estudiante? " + esEstudiante);
    }
}
