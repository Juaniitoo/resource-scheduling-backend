# Resource & Scheduling Management System

Backend genérico para empresas que permite gestionar recursos y tareas/turnos,
detectar conflictos de planificación automáticamente y obtener estadísticas de uso.
Diseñado para ser escalable, seguro y adaptable a distintos sectores.

## MVP Scope

The MVP includes:
- Users with roles (ADMIN, MANAGER, VIEWER)
- Resource management (rooms, machines, vehicles, etc.)
- Tasks/turns with start and end time
- Assignment of users and resources to tasks
- Automatic conflict detection (overlapping schedules)
- Basic usage statistics

## Core Entities

### User
Represents a person using the system.
Has a role and can be assigned to tasks.

### Resource
Represents any shared asset (room, machine, vehicle, etc.)
Can be assigned to tasks but cannot overlap in time.

### Task
Represents a scheduled activity with start and end time.
Can have assigned users and resources.
