# SOFTWARE FJ – Fase 4

## Sistema Integral de Gestión de Clientes, Servicios y Reservas

**Universidad:** Universidad Nacional Abierta y a Distancia (UNAD)  
**Curso:** Programación  
**Código:** 213023  
**Actividad:** Fase 4 – Prácticas simuladas  
**Lenguaje de programación:** Python

---

## 1. Descripción del proyecto

Software FJ es un sistema desarrollado en Python que permite gestionar clientes, servicios y reservas de una empresa dedicada a ofrecer espacios, equipos y asesorías especializadas.

El sistema permite registrar clientes, administrar diferentes tipos de servicios, crear reservas, confirmar solicitudes, cancelar reservas y calcular los costos correspondientes.

El proyecto aplica los principios de programación orientada a objetos y mecanismos de manejo de excepciones para garantizar una gestión organizada de la información.

## 2. Objetivo general

Desarrollar un sistema integral de gestión utilizando Python y programación orientada a objetos, que permita administrar clientes, servicios y reservas mediante diferentes funcionalidades y validaciones.

## 3. Objetivos específicos

- Implementar clases y objetos para representar los elementos del sistema.
- Aplicar los principios de abstracción, herencia, polimorfismo y encapsulación.
- Desarrollar mecanismos para registrar y consultar clientes.
- Gestionar servicios de salas, alquiler de equipos y asesorías especializadas.
- Crear, confirmar, procesar y cancelar reservas.
- Implementar excepciones personalizadas y registros de eventos y errores.

## 4. Tecnologías utilizadas

- Python 3.
- Visual Studio Code.
- GitHub.
- Programación orientada a objetos.
- Módulo logging de Python.

## 5. Estructura del proyecto

```text
Software-FJ-Fase4/
│
├── clientes.py
├── entidades.py
├── excepciones.py
├── main.py
├── reservas.py
├── servicios.py
├── sistema.py
├── README.md
└── software_fj.log
```

## 6. Descripción de los archivos

| Archivo | Función |
|---|---|
| clientes.py | Gestión y validación de clientes. |
| entidades.py | Clase abstracta Entidad. |
| excepciones.py | Excepciones personalizadas. |
| main.py | Programa principal y pruebas. |
| reservas.py | Gestión de reservas y procesamiento. |
| servicios.py | Clase abstracta Servicio y servicios especializados. |
| sistema.py | Administración general del sistema. |
| software_fj.log | Registro de eventos y errores. |

## 7. Funcionalidades principales

El sistema permite:

1. Registrar clientes.
2. Validar información de los clientes.
3. Registrar servicios.
4. Gestionar reservas de salas.
5. Administrar alquileres de equipos.
6. Gestionar asesorías especializadas.
7. Crear reservas.
8. Confirmar reservas.
9. Procesar reservas y calcular costos.
10. Cancelar reservas.
11. Controlar datos incorrectos.
12. Registrar eventos y errores.

## 8. Principios de programación orientada a objetos

**Abstracción:** se implementan clases abstractas para representar entidades y servicios.

**Herencia:** las clases Cliente y Servicio especializado utilizan estructuras de herencia según su relación con las clases principales.

**Polimorfismo:** los servicios implementan métodos propios para describir y calcular sus costos.

**Encapsulación:** se protegen determinados atributos mediante atributos privados y propiedades de acceso.

**Manejo de excepciones:** se utilizan excepciones personalizadas para controlar errores durante la ejecución.

## 9. Instrucciones de ejecución

Para ejecutar el proyecto se deben seguir estos pasos:

1. Descargar el repositorio desde GitHub.
2. Extraer los archivos del proyecto.
3. Abrir la carpeta en Visual Studio Code.
4. Verificar que Python esté instalado.
5. Abrir una terminal dentro de la carpeta del proyecto.
6. Ejecutar el siguiente comando:

```bash
py main.py
```

También se puede utilizar:

```bash
python main.py
```

## 10. Registro de eventos y errores

El sistema utiliza el módulo logging de Python para registrar eventos, operaciones y errores durante su funcionamiento.

Los registros permiten realizar un seguimiento de las actividades ejecutadas y facilitan la identificación de posibles inconvenientes.

## 11. Repositorio del proyecto

**GitHub:**

https://github.com/edinsonmontano72-blip/Software-FJ-Fase4

## 12. Conclusión

El desarrollo de Software FJ permitió aplicar los fundamentos de programación orientada a objetos mediante la construcción de un sistema para gestionar clientes, servicios y reservas.

Durante su implementación se utilizaron clases, objetos, herencia, abstracción, encapsulación, polimorfismo y manejo de excepciones, logrando desarrollar una aplicación organizada y funcional.

Asimismo, las pruebas realizadas permitieron comprobar las funcionalidades principales del sistema y fortalecer los conocimientos adquiridos durante el desarrollo del curso.
