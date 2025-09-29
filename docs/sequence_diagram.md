```mermaid
sequenceDiagram
    actor Paciente
    actor Doctor
    participant Sistema

    Paciente ->> Sistema: Solicitar Cita(fecha,hora)
    Sistema ->> Doctor: Verificar Disponibilidad
    Doctor -->> Sistema: Confirmar disponibilidad
    Sistema ->> Paciente: Confirmación de cita
```