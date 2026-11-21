# Control de Horario

Aplicación web completa para la gestión de empleados y control de horas de trabajo. Diseñada para registrar la jornada laboral, gestionar pausas y calcular horas trabajadas de manera eficiente.

## Características

- **Gestión de Empleados**: Agregar, editar y eliminar empleados con DNI/NIE y fotos de perfil
- **Control de Jornada**: Registrar entrada, salida y pausas en tiempo real
- **Cálculo de Horas**: Cálculo automático de horas trabajadas en rangos de fechas seleccionados
- **Desglose de Jornadas**: Visualización detallada de sesiones de trabajo con horarios de inicio y fin
- **Backup y Restore**: Crear copias de seguridad de los datos por rango de fechas
- **Búsqueda y Filtros**: Buscar empleados por nombre, puesto o DNI
- **Interfaz Responsiva**: Diseño optimizado para móvil y escritorio con Tailwind CSS

## Tecnologías

- **HTML5 / CSS3** con Tailwind CSS
- **Google Fonts**: Inter
- **IndexedDB**: Almacenamiento de datos en el navegador
- **JavaScript Vanilla**: Sin dependencias externas

## Instalación

1. Clona el repositorio:
   ```bash
   git clone https://github.com/tu-usuario/control-horario.git
   ```

2. Abre `app.html` en tu navegador preferido. La aplicación funciona completamente en el cliente, no requiere servidor ni backend.

## Uso

### Gestión de Empleados
- Haz clic en "Añadir Empleado" para registrar un nuevo trabajador
- Usa la búsqueda para encontrar empleados rápidamente
- Haz clic en una tarjeta de empleado para ver sus detalles y estado actual

### Control de Horas
- En la vista de detalle del empleado, verás su estado actual (Trabajando, En Pausa, Fuera de servicio)
- Usa los botones de acción para registrar entrada, salida o pausas
- Selecciona un rango de fechas para calcular las horas trabajadas en ese periodo
- El desglose muestra cada jornada con sus horarios de inicio y fin

### Backup de Datos
- Haz clic en "Crear Backup" en la navegación superior
- Selecciona el rango de fechas deseado
- Descarga el archivo JSON con todos los datos de empleados y registros horarios

## Estructura del Proyecto

```
control-horario/
├── app.html          # Archivo principal de la aplicación (HTML, CSS, JS)
```

## Licencia

MIT


