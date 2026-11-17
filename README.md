# Kubernetes

Repositorio con mis apuntes y prácticas mientras aprendo Kubernetes, desde los conceptos básicos hasta el despliegue de aplicaciones.

## Contenido

| Nº | Tema | Descripción |
|----|------|-------------|
| 1 | [Introducción](docs/1-Introduccion.md) | Qué es Kubernetes, para qué sirve y su arquitectura (clúster, nodos, plano de control). |
| 2 | [Instalación](docs/2-Instalacion.md) | Montaje del entorno de trabajo: clúster local con Minikube, `kubectl` y autocompletado. |
| 3 | [Pods](docs/3-PODS.md) | La unidad mínima de Kubernetes: cómo crear, inspeccionar y eliminar Pods. |
| 4 | [ReplicaSets](docs/4-ReplicaSets.md) | Cómo mantener un número fijo de réplicas de un Pod. |
| 5 | [Deployments](docs/5-Deployement.md) | Despliegue de aplicaciones, actualizaciones progresivas y rollbacks. |

## Estructura del repositorio

```
kubernetes/
├── README.md
├── LICENSE
├── docs/
│   ├── 1-Introduccion.md
│   ├── 2-Instalacion.md
│   ├── 3-PODS.md
│   ├── 4-ReplicaSets.md
│   └── 5-Deployement.md
└── img/                  # Capturas, una carpeta por cada tema
    └── 2-Instalacion/
```

## Cómo usar este repositorio

Los temas están pensados para leerse en orden: cada uno se apoya en lo visto en el anterior.

```bash
git clone https://github.com/danielgonhid/kubernetes.git
cd kubernetes
```

## Requisitos

- Conocimientos básicos de Linux y de la terminal.
- Nociones de contenedores (Docker).
- Un clúster de Kubernetes para las prácticas (en el tema 2 se explica cómo montarlo).

## Autor

**Daniel González Hidalgo**

## Licencia

Este proyecto se distribuye bajo la licencia incluida en el archivo [LICENSE](LICENSE).
