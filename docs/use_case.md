```mermaid
usecaseDiagram
    actor Doctor
    actor Paciente
    actor Administrador

    Paciente --> (Registrarse)
    Paciente --> (Agendar Cita)
    Paciente --> (Cancelar Cita)
    Paciente --> (Consultar Historial)

    Doctor --> (Ver Agenda)
    Doctor --> (Registrar Diagnóstico)
    Doctor --> (Confirmar/Cancelar Cita)

    Administrador --> (Gestionar Usuarios)
    Administrador --> (Generar Reportes)
```