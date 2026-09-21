# Pedidos Cusco

Sistema web para gestionar pedidos de comida local en Cusco. Proyecto desarrollado como caso práctico del **Laboratorio 1: Introducción al entorno de desarrollo y Git** (Ingeniería de Software I).

## Contexto

Una startup en Cusco quiere ofrecer una plataforma web donde los restaurantes locales publiquen su carta y los clientes hagan pedidos en línea. El equipo necesita organizar su código desde el inicio, por lo que el proyecto usa Git y GitHub para el control de versiones.

## Objetivos del sistema

- Permitir a los clientes ver restaurantes y platos de comida local.
- Registrar y hacer seguimiento de los pedidos.
- Dar a los restaurantes un panel para gestionar su carta y los pedidos recibidos.

## Funcionalidades previstas

| Módulo | Descripción |
|---|---|
| Clientes | Registro, inicio de sesión y perfil |
| Catálogo | Restaurantes, platos, precios y disponibilidad |
| Pedidos | Carrito, confirmación y estado del pedido |
| Restaurantes | Gestión de carta y pedidos recibidos |

> Estado actual: proyecto inicial. Aún no hay código de la aplicación.

## Herramientas

- Visual Studio Code
- Git
- GitHub

## Flujo de trabajo con Git

```bash
git init                                   # inicializar el repositorio
git add .                                  # preparar los cambios
git commit -m "Primer commit"              # guardar una versión
git remote add origin <URL>                # conectar con GitHub
git push -u origin main                    # subir la rama main
```

## Estructura del repositorio

```
pedidos-cusco/
└── README.md
```

## Reflexión

**¿Por qué Git es crítico en proyectos colaborativos?**

Git guarda el historial completo del código: quién cambió qué, cuándo y por qué. Así varias personas trabajan a la vez, cada una en su propia rama, y luego integran sus cambios sin pisarse. Además, cada versión queda guardada, por lo que siempre se puede volver a un estado que funcionaba. Con un remoto como GitHub, todo el equipo comparte la misma fuente de verdad y puede revisar el trabajo de los demás antes de integrarlo.

**¿Qué problemas evita?**

- Perder código por errores, borrados accidentales o fallos del equipo.
- Sobrescribir el trabajo de otro compañero al editar los mismos archivos.
- Tener copias sueltas como `proyecto_final_v2_definitivo`, sin saber cuál es la buena.
- No saber quién hizo un cambio ni por qué, lo que complica encontrar el origen de un error.
- Que un cambio con fallos deje todo el proyecto sin funcionar, porque se puede revertir.

## Autor

- 007chino — 141002@unsaac.edu.pe (UNSAAC)
