# SYSTEM TRIAGE 

# Diagramas del Modelo de Datos

Este repositorio incluye los diagramas de diseño inicial del modelo de datos del sistema de triaje hospitalario. A continuación se describen los dos artefactos principales: el **Diagrama Entidad-Relación (DER)** y el **Diagrama de Clases**.

---

## 🗃️ Diagrama Entidad-Relación (DER)

Propuesta inicial del modelo relacional de la base de datos, diseñada con [dbdiagram.io](https://dbdiagram.io/).  
Incluye las 20 tablas definidas en las categorías de seguridad, clínicos, infraestructura, agenda, triage, notificaciones y auditoría.

🔗 **[Ver diagrama en dbdiagram.io](https://dbdiagram.io/d/Software-Triaje-68dae786d2b621e4227783b5)**

Además, se proporciona un script SQL listo para PostgreSQL que crea todas las tablas, relaciones, restricciones e índices iniciales.

---

## 🧠 Diagrama de Clases

Modelo orientado a objetos que define las clases correspondientes a cada entidad, junto con sus atributos y métodos esenciales (CRUD y lógica básica).  
Diseñado con [Mermaid Chart](https://www.mermaidchart.com/), compatible con la sintaxis de Mermaid v10+.

🔗 **[Ver diagrama en Mermaid Chart](https://www.mermaidchart.com/d/7a0c87d9-6876-4718-a4c4-3eee208f6468)**

> 💡 ¿Quieres proponer mejoras? Crea una cuenta en Mermaid Chart y deja tus comentarios directamente en el diagrama.

---
Este diseño sirve como base para el desarrollo backend, generación de migraciones y definición de APIs. ¡Contribuciones y sugerencias son bienvenidas!
