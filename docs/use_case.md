graph TD
    Paciente --> Registrarse
    Paciente --> AgendarCita[Agendar Cita]
    Paciente --> CancelarCita[Cancelar Cita]
    Paciente --> ConsultarHistorial[Consultar Historial]

    Doctor --> VerAgenda[Ver Agenda]
    Doctor --> RegistrarDiagnostico[Registrar Diagnóstico]
    Doctor --> ConfirmarCancelarCita[Confirmar/Cancelar Cita]

    Administrador --> GestionarUsuarios[Gestionar Usuarios]
    Administrador --> GenerarReportes[Generar Reportes]
