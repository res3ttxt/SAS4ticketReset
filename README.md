# ⚡ SAS 4 - Black Ticket Reset

Un práctico programa diseñado para restablecer de manera segura el tiempo de espera (*cooldown*) de los tickets de partidas en modo **Nightmare / Black** de **SAS: Zombie Assault 4** (Versión de Steam).

---

## 📋 Requisitos para el Funcionamiento
Para que el programa funcione correctamente, el usuario debe cumplir con los siguientes requisitos:
1. **Tener el juego instalado mediante Steam** (se soportan instalaciones en discos secundarios como el disco local `D:`, `E:`, etc.).
2. **Haber iniciado sesión en Steam** al menos una vez en el equipo.
3. **Tener una partida guardada activa** en el juego (con al menos un personaje creado).

---

## 🚀 Modo de Uso

Sigue estos sencillos pasos para usar la herramienta:

1. **Cierra el juego por completo** antes de abrir el reseteador de tickets.
2. **Ejecuta el archivo ejecutable (`SAS4TicketReset.exe`)**.
   * *Nota: Si es la primera vez que lo usas, el programa te solicitará seleccionar tu cuenta de Steam activa y tu personaje principal en una ventana de diálogo.*
3. Una vez dentro de la interfaz principal:
   * Podrás ver los datos del **Personaje Activo** (Nombre, Clase, Nivel, SAS Cash).
   * Verás una tarjeta indicando el **Estado del Ticket**:
     * ⏳ **TICKET CON TIEMPO DE ESPERA (COOLDOWN)**: Significa que debes esperar para volver a jugar.
     * ✓ **TICKET LISTO PARA JUGAR**: Ya puedes ingresar directamente sin esperar.
4. Haz clic en el botón **🔄 RESETEAR COOLDOWN DE TICKET**.
5. ¡Listo! Recibirás una notificación verde (*Toast*) indicando el éxito de la operación. Abre tu juego y disfruta de una nueva partida.

### 👥 Cambiar de Personaje
Si tienes múltiples personajes creados en la misma cuenta, puedes alternar entre ellos utilizando el botón **👥 Cambiar Personaje** ubicado en la esquina inferior izquierda.

### 🔄 Actualizar Datos
Si acabas de terminar una partida en el juego y deseas ver tus estadísticas más recientes (nivel, SAS Cash o estado de ticket) en la pantalla del reseteador, haz clic en el botón **🔄 Actualizar Datos** en la parte inferior. Esto recargará tu partida guardada al instante sin necesidad de reiniciar el programa.

---

## 💡 Consejos Importantes y Seguridad

> [!IMPORTANT]
> **1. NUNCA resetees el ticket con el juego abierto**
> Steam mantiene los datos de guardado en la memoria RAM mientras juegas. Si usas el reseteador con el juego abierto, corres el riesgo de perder el progreso reciente (como armas, núcleos/cores o dinero ganados en tu última partida) debido a un choque de sincronización.
>
> *Por seguridad, el programa cuenta con un bloqueador integrado que no te permitirá aplicar el reseteo si detecta que el juego está abierto.*


> [!WARNING]
> **3. Ejecutar como Administrador**
> Si el programa se abre y muestra directamente el error *"No se detectó partida de SAS 4"*, pero estás seguro de tener el juego instalado y con sesión iniciada, haz clic derecho sobre el ejecutable y selecciona **Ejecutar como administrador**. Esto le otorga los permisos necesarios para leer el Registro de Windows y las carpetas del sistema.

---

## 🛠️ Resolución de Problemas (FAQ)

### ❓ Presiono "Reintentar detección" y no pasa nada
Asegúrate de que Steam esté abierto y que hayas iniciado sesión en tu cuenta. Una vez que hayas iniciado sesión de forma normal, haz clic en **Reintentar detección** y el programa detectará automáticamente tu perfil de guardado.

---

*Desarrollado por y_alucard.*
