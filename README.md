# Nexus — Documentación

Documentación del proyecto **Nexus**, Sistema de Información para Hogares Geriátricos.

Centro de Gestión de Mercados, Logística y Tecnologías de la Información — SENA · Ficha 3407184

**Integrantes:**

- Carreño Cardozo Dilan Santiago
- López Rodríguez Susan Valeria
- Luque Aguirre Jarek Nicolás
- Nocua Carrillo Joshua David

El código del sistema está en su propio repositorio. Este repositorio solo contiene los documentos.

---

## Contenido

| Archivo | Para qué sirve |
|---|---|
| `Nexus General.pdf` | Qué hace Nexus, actores, requisitos, arquitectura, base de datos y metodología. Es el documento base. |
| `Requisitos Nexus.xlsx` | Requisitos funcionales y no funcionales, con una hoja de historia de usuario por cada RF. |
| `Manual de Usuario Nexus.pdf` | Cómo usar Nexus según el rol: administrador, cuidador y familiar. |
| `Manual de Instalación Nexus.pdf` | Instalación en Windows con XAMPP, en un servidor Linux y con Docker en Railway; variables de configuración y problemas comunes. |
| `Plan de Pruebas Nexus.pdf` | Cómo se prueba el sistema: base de prueba, usuarios de prueba, tipos de prueba y criterios de entrada y salida. |
| `Casos de Prueba Nexus.xlsx` | 113 casos de prueba con pasos, resultado esperado, resultado obtenido y estado. |
| `Informe de Hallazgos Nexus.pdf` | Puntos por mejorar encontrados en el código, ordenados por importancia. |
| `Plan de Respaldo Nexus.pdf` | Copias de seguridad de la base de datos y cómo recuperarlas. |

## Por dónde empezar

- **Entender el sistema:** `Nexus General.pdf`.
- **Usarlo:** `Manual de Usuario Nexus.pdf`.
- **Instalarlo o publicarlo:** `Manual de Instalación Nexus.pdf` (la sección 3.8 explica Railway).
- **Probarlo:** `Plan de Pruebas Nexus.pdf` y luego `Casos de Prueba Nexus.xlsx`.
- **Copias de seguridad:** `Plan de Respaldo Nexus.pdf`.

## Cómo se relacionan los documentos

```
Requisitos Nexus.xlsx ──► Nexus General.pdf ──► Casos de Prueba Nexus.xlsx
                                  │                        │
                                  │                Plan de Pruebas Nexus.pdf
                                  │
        Manual de Usuario · Manual de Instalación · Plan de Respaldo
                                  │
                      Informe de Hallazgos Nexus.pdf
```

- Cada caso de prueba (`CP-RFxx-yy`) corresponde a un requisito (`RFxx` o `RNFxx`).
- Los hallazgos (`H01` a `H26`) del informe se citan en los casos de prueba y en los manuales.
- Los errores encontrados al probar se anotan como `DEF-001`, `DEF-002`…

## Notas

- Los usuarios y contraseñas de prueba que aparecen en los documentos (`admin`, `cuidador`, `familiar`) son solo para pruebas. No se deben usar en un servidor real.
- Los documentos contienen datos de ejemplo, no información real de residentes.     

  Equipo Nexus. 💙
