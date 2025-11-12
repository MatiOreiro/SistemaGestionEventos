# Sistema de Gestión de Eventos / Event Management System

<div align="center">

![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![NetBeans](https://img.shields.io/badge/NetBeans-1B6AC6?style=for-the-badge&logo=apachenetbeanside&logoColor=white)
![Status](https://img.shields.io/badge/Status-Completed-success?style=for-the-badge)

</div>

---

## 🌐 Language / Idioma

- [🇪🇸 Español](#español)
- [🇬🇧 English](#english)

---

<a name="español"></a>
## 🇪🇸 Español

### 📋 Descripción

Sistema de gestión de eventos desarrollado como proyecto obligatorio para la materia **Algoritmos y Estructuras de Datos** de la Universidad ORT Uruguay. El sistema permite administrar salas, eventos, clientes y entradas utilizando estructuras de datos personalizadas.

### ✨ Características Principales

- **Gestión de Salas**: Registro y eliminación de salas con validación de capacidad
- **Gestión de Eventos**: Creación de eventos con asignación automática de salas disponibles
- **Gestión de Clientes**: Registro de clientes con validación de cédula (8 dígitos)
- **Sistema de Entradas**: Compra y devolución de entradas con lista de espera automática
- **Análisis de Salas**: Algoritmo para determinar si una sala es óptima según criterios específicos
- **Calificaciones**: Sistema de puntuación y comentarios para eventos

### 🏗️ Arquitectura

El proyecto implementa estructuras de datos propias:
- **Listas Simplemente Enlazadas**: Para almacenar salas, eventos y clientes
- **Colas**: Para gestionar listas de espera de entradas
- **Nodos**: Implementación básica de nodos enlazados

### 🛠️ Tecnologías Utilizadas

- **Lenguaje**: Java
- **IDE**: NetBeans
- **Testing**: JUnit
- **Build**: Apache Ant

### 📁 Estructura del Proyecto

```
Sistema de Eventos Marzo 2025/
├── src/
│   ├── dominio/           # Clases de dominio (Cliente, Evento, Sala, etc.)
│   ├── sistemaAutogestion/ # Lógica principal del sistema
│   └── tads/              # Estructuras de datos (Listas, Colas, Nodos)
├── test/                  # Pruebas unitarias
├── build/                 # Archivos compilados
└── nbproject/             # Configuración de NetBeans
```

### 🚀 Cómo Ejecutar

1. **Clonar el repositorio**
   ```bash
   git clone https://github.com/tu-usuario/sistema-eventos.git
   ```

2. **Abrir en NetBeans**
   - Abrir NetBeans IDE
   - File → Open Project
   - Seleccionar la carpeta "Sistema de Eventos Marzo 2025"

3. **Compilar y Ejecutar**
   - Click derecho en el proyecto → Build
   - Click derecho en el proyecto → Run

### 🧪 Ejecutar Tests

```bash
# Desde NetBeans
Click derecho en el proyecto → Test
```

### 📊 Funcionalidades Implementadas

#### Gestión Básica
- ✅ Crear sistema de gestión
- ✅ Registrar sala (con validaciones)
- ✅ Eliminar sala
- ✅ Registrar evento (con asignación automática de sala)
- ✅ Registrar cliente
- ✅ Comprar entrada
- ✅ Eliminar evento
- ✅ Devolver entrada

#### Consultas y Reportes
- ✅ Listar salas
- ✅ Listar eventos (ordenados por código)
- ✅ Listar clientes (ordenados por cédula)
- ✅ Verificar si sala es óptima
- ✅ Listar clientes de un evento
- ✅ Listar eventos en lista de espera
- ✅ Calificar eventos
- ✅ Evento mejor puntuado
- ✅ Compras por cliente
- ✅ Compras por día

### 📝 Códigos de Error

| Código | Descripción |
|--------|-------------|
| ERROR_1 | El elemento ya existe / No se encontró |
| ERROR_2 | Dato inválido (capacidad, aforo, cédula) |
| ERROR_3 | No hay sala disponible |

### 👨‍🎓 Autor

**Matías Oreiro**
- Cédula: 239479
- Universidad: ORT Uruguay
- Carrera: Analista en Tecnologías de la Información
- Docente: Sebastián Pesce
- Fecha: Mayo 2025

### 📄 Licencia

Este proyecto fue desarrollado con fines académicos para la Universidad ORT Uruguay.

---

<a name="english"></a>
## 🇬🇧 English

### 📋 Description

Event management system developed as a mandatory project for the **Algorithms and Data Structures** course at Universidad ORT Uruguay. The system allows managing venues, events, clients, and tickets using custom data structures.

### ✨ Key Features

- **Venue Management**: Registration and deletion of venues with capacity validation
- **Event Management**: Event creation with automatic available venue assignment
- **Client Management**: Client registration with ID validation (8 digits)
- **Ticketing System**: Ticket purchase and return with automatic waiting list
- **Venue Analysis**: Algorithm to determine if a venue is optimal according to specific criteria
- **Ratings**: Scoring and comment system for events

### 🏗️ Architecture

The project implements custom data structures:
- **Singly Linked Lists**: To store venues, events, and clients
- **Queues**: To manage ticket waiting lists
- **Nodes**: Basic implementation of linked nodes

### 🛠️ Technologies Used

- **Language**: Java
- **IDE**: NetBeans
- **Testing**: JUnit
- **Build**: Apache Ant

### 📁 Project Structure

```
Sistema de Eventos Marzo 2025/
├── src/
│   ├── dominio/           # Domain classes (Client, Event, Venue, etc.)
│   ├── sistemaAutogestion/ # Main system logic
│   └── tads/              # Data structures (Lists, Queues, Nodes)
├── test/                  # Unit tests
├── build/                 # Compiled files
└── nbproject/             # NetBeans configuration
```

### 🚀 How to Run

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/event-system.git
   ```

2. **Open in NetBeans**
   - Open NetBeans IDE
   - File → Open Project
   - Select "Sistema de Eventos Marzo 2025" folder

3. **Compile and Run**
   - Right-click on project → Build
   - Right-click on project → Run

### 🧪 Run Tests

```bash
# From NetBeans
Right-click on project → Test
```

### 📊 Implemented Features

#### Basic Management
- ✅ Create management system
- ✅ Register venue (with validations)
- ✅ Delete venue
- ✅ Register event (with automatic venue assignment)
- ✅ Register client
- ✅ Purchase ticket
- ✅ Delete event
- ✅ Return ticket

#### Queries and Reports
- ✅ List venues
- ✅ List events (sorted by code)
- ✅ List clients (sorted by ID)
- ✅ Check if venue is optimal
- ✅ List clients of an event
- ✅ List events on waiting list
- ✅ Rate events
- ✅ Best-rated event
- ✅ Purchases by client
- ✅ Purchases by day

### 📝 Error Codes

| Code | Description |
|------|-------------|
| ERROR_1 | Element already exists / Not found |
| ERROR_2 | Invalid data (capacity, attendance, ID) |
| ERROR_3 | No venue available |

### 👨‍🎓 Author

**Matías Oreiro**
- Student ID: 239479
- University: ORT Uruguay
- Program: Information Technology Analyst
- Professor: Sebastián Pesce
- Date: May 2025

### 📄 License

This project was developed for academic purposes at Universidad ORT Uruguay.

---

<div align="center">

**⭐ If you found this project useful, consider giving it a star!**

Made with ❤️ by [Matías Oreiro](https://github.com/tu-usuario)

</div>
