# ReactPro Tickets

Es una aplicación de  Sistema de Gestión para la Acreditación del Personal Interno y Externo Participante en Procesos Electorales.

En dicha aplicación se muestran 4 estados: abierto, en progreso, verificación y completado
-	Cuando se llena en formulario para la participación del evento “Abierto”
-	Cuando el usuario se registra para el evento “En progreso”
-	Cuando el usuario es incluido en la data de participación “Verificación”

- Cuando se emite la credencial de participación “Completado” 


# Entidades

## Credencial

- Documento de Identidad
- Nombre y Apellido del Acreditado
- Foto
- Fecha del Evento al cual esta acreditado


## Usuario

- Nombre
- Correo

## Verfificacion

- Base de datos del registro


# Relaciones

-	Una credencial tiene un Usuario
-	Un Usuario  tiene asignado una credencial

# Funciones

-	Crea usuario
-	Edita usuario
-	Autoriza credencial
-	Captura foto
-	Genera credencial
-	Imprime credencial


# Pantallas

-	Formulario de registro
-	Crear/editar registro
-	Inclusión en base de datos
-	Perfil del usuario
-	Crear/editar usuario
-	Captura de imagen
-	Editar/actualizar imagen
-	Eventos electorales
-	Estatus del evento 
-	Procesar/anular participación
-	Confirmación del proceso
-	Demostración de la acreditación para ser impresas


