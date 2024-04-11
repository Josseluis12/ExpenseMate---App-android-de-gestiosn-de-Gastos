# Bienvenido a la App de Gastos Compartidos y la API correspondiente 📱💻

¡Hola amigo/a! ¿Estás listo/a para sumergirte en el mundo de los gastos compartidos? ¡Este es el lugar indicado! Aquí te guiaremos a través de la aplicación de Android y la API que hemos creado para facilitar la gestión de tus finanzas compartidas.

## App de Android 📱

La aplicación de Android es tu compañera perfecta para organizar los gastos con tus amigos, compañeros de piso o equipo de trabajo. Con esta app, puedes crear proyectos, registrar gastos y mantener un registro de quién debe qué.

### Funcionalidades Destacadas

- **Registro e Inicio de Sesión:** ¡Empieza creando tu cuenta o accede si ya tienes una!
- **Gestión de Proyectos:** Crea nuevos proyectos y únete a los existentes.
- **Registro de Gastos:** Registra cada gasto que realices y mantén un registro claro.
- **Resumen de Gastos:** Visualiza fácilmente cuánto has gastado y quién ha contribuido.

## API 🌐

Nuestra API es la columna vertebral de la aplicación, proporcionando acceso a la base de datos y facilitando la interacción entre la app y el servidor.

### Principales Endpoints

- **/register:** Registra nuevos usuarios en la plataforma.
- **/login:** Inicia sesión con tu cuenta registrada.
- **/projects:** Gestiona proyectos (crear, actualizar, eliminar).
- **/expenses:** Registra y gestiona gastos en los proyectos.
- **/users:** Obtiene información detallada sobre los usuarios registrados.

### ¿Cómo Empezar?

1. **Configuración del Entorno:** Asegúrate de tener Python y MySQL instalados en tu sistema.
2. **Configuración de la Base de Datos:** Crea una base de datos MySQL y establece la URL de conexión en la variable de entorno `SQLALCHEMY_DATABASE_URI`.
3. **Ejecución de la API:** Inicia el servidor de la API y empieza a disfrutar de todas las funcionalidades.

### Ejemplo de Uso

**Registro de Usuario**
```
POST /register
{
  "username": "ejemplo",
  "password": "contraseña"
}
```
**Inicio de Sesión**
```
POST /login
{
  "username": "ejemplo",
  "password": "contraseña"
}
```
**Obtener Proyectos**
```
GET /projects
```

¡Y eso es todo! Si tienes alguna pregunta o necesitas ayuda, ¡no dudes en contactarnos! Estamos aquí para asegurarnos de que tu experiencia con la app y la API sea excepcional. ¡Disfruta gestionando tus gastos compartidos! 😊💼
