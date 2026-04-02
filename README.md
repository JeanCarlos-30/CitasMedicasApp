# CitasMedicasApp

Aplicación web para la gestión de citas médicas, desarrollada en **ASP.NET Core MVC**.  
El proyecto sigue una arquitectura organizada en capas para facilitar el mantenimiento y la escalabilidad.

---

##  Estructura del proyecto

- **Controllers/**  
  Contiene los controladores principales de la aplicación:
  - `AuthController.cs` → Manejo de autenticación y registro de usuarios.
  - `AppointmentsController.cs` → Gestión de citas médicas.
  - `DoctorsController.cs` → Administración de doctores.
  - `PatientsController.cs` → Administración de pacientes.

- **Models/**  
  Define las entidades del sistema:
  - `User.cs`, `Doctor.cs`, `Patient.cs`, `Appointment.cs`.

- **Views/**  
  Contiene las vistas en Razor (`.cshtml`) organizadas por módulo:
  - `Auth/` → Login y registro.
  - `Appointments/` → Listado, creación, edición y detalles de citas.
  - `Doctors/` → Listado y gestión de doctores.
  - `Shared/` → Layouts y vistas compartidas.

- **Services/**  
  Lógica de negocio y servicios auxiliares:
  - `AppointmentService.cs`, `NotificationService.cs`, `UserService.cs`.

- **Data/**  
  Acceso a datos y configuración de Entity Framework:
  - `ApplicationDbContext.cs`
  - `Migrations/`

- **wwwroot/**  
  Archivos estáticos (CSS, JS, imágenes).

- **Archivos raíz**  
  - `Program.cs` → Punto de entrada de la aplicación.  
  - `Startup.cs` → Configuración inicial (middlewares, servicios).  
  - `appsettings.json` → Configuración de la aplicación.  
  - `README.md` → Documentación del proyecto.

---


