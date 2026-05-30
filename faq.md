

----
```
- Para instalar una VPN, para hacer teletrabajo, que características tiene que tener el ordenador?

```


Para instalar y usar una VPN destinada al teletrabajo, no necesitas un superordenador, pero sí ciertos mínimos para que la conexión sea fluida, segura y no ralentice el resto de tus herramientas (como videollamadas o bases de datos).

Aquí tienes las características clave que debe cumplir el equipo:

### 1. Memoria RAM (Lo más crítico)

La VPN en sí no consume demasiada memoria, pero al teletrabajar estarás ejecutando la VPN **más** las herramientas de la empresa (Teams, Zoom, navegadores con decenas de pestañas, entornos de desarrollo, etc.).

* **Mínimo:** 8 GB de RAM.
* **Recomendado:** **16 GB de RAM o más.** Esto garantiza que el cifrado de datos de la VPN en segundo plano no ralentice tus videollamadas o aplicaciones de trabajo.

### 2. Procesador (CPU)

El tráfico de una VPN se cifra y descifra constantemente en tiempo real, lo que requiere un esfuerzo del procesador.

* **Mínimo:** Intel Core i5 / AMD Ryzen 5 (de generaciones recientes) o chips Apple M1/M2/M3.
* **Clave técnica:** Es ideal que el procesador cuente con soporte para **AES-NI** (instrucciones de cifrado por hardware), algo que casi todos los procesadores de los últimos 5-7 años ya incluyen. Esto hace que el impacto de la VPN en el rendimiento del sistema sea casi imperceptible.

### 3. Sistema Operativo

Dependerá del software específico que utilice tu empresa (Cisco AnyConnect, FortiClient, OpenVPN, WireGuard, etc.).

* **Windows:** Windows 10 o Windows 11 (preferiblemente versiones Pro si la empresa requiere políticas de seguridad específicas).
* **Linux:** Distribuciones estables y actualizadas (como **Ubuntu LTS**). La mayoría de VPNs corporativas tienen soporte nativo o mediante OpenVPN/WireGuard en terminal.
* **macOS:** Versiones recientes con soporte oficial del fabricante.

> **Nota de seguridad:** El sistema operativo debe estar **original y completamente actualizado** con los últimos parches de seguridad; muchas VPN corporativas hacen un chequeo previo y, si detectan un sistema desactualizado, deniegan el acceso.

### 4. Almacenamiento

* **Imprescindible:** Disco duro **SSD**. Un disco mecánico tradicional (HDD) ralentizará drásticamente el sistema cuando la VPN esté gestionando archivos temporales o sincronizando datos con los servidores de la empresa.

### 5. Conectividad y Red (Fundamental)

De nada sirve un buen ordenador si la conexión no acompaña.

* **Tarjeta de red:** Tarjeta Wi-Fi de doble banda (5 GHz) o, idealmente, conexión por cable Ethernet (RJ45) para evitar microcortes que puedan tirar la sesión de la VPN.
* **Velocidad de internet:** Mínimo 30-50 Mbps de bajada y subida (fibra óptica). Ten en cuenta que **las VPN siempre reducen un porcentaje de tu velocidad de internet habitual** debido al proceso de cifrado y a la distancia del servidor de la empresa.

---

En resumen, cualquier portátil o sobremesa de gama media actual (con un buen procesador, **16 GB de RAM y un disco SSD**) gestionará una VPN de teletrabajo sin despeinarse.

¿Sabes ya qué software de VPN específico vas a tener que instalar, o te da la empresa alguna pauta de seguridad concreta?




----
```
- Tengo un portatil, con Windows 11, pero va un poco lento porque el disco duro esta bastante lleno, etc... Ayúdame a dejarlo como el primer día que lo compré

```

Para dejar tu portátil con Windows 11 "como el primer día", tienes dos caminos. El primero es hacer una **limpieza y optimización a fondo** (para no perder nada), y el segundo es la **solución definitiva: restablecer el sistema de fábrica**, que borra lo innecesario y reinstala Windows limpio.

Dado que el disco está bastante lleno y eso es lo que más ralentiza Windows 11, vamos a ver los pasos ordenados de menos a más drásticos.

---

## Opción 1: La solución definitiva (Restablecer de fábrica)

Si quieres cortar por lo sano y recuperar la velocidad original saltándote configuraciones pesadas, esta es la mejor opción.

> ⚠️ **IMPORTANTE:** Antes de hacer esto, copia todos tus archivos importantes (documentos, fotos, códigos, proyectos) a un disco duro externo o a la nube (Google Drive, OneDrive, etc.). Aunque Windows te da la opción de conservar tus archivos, **las aplicaciones se borrarán** y siempre es más seguro tener copia de respaldo.

1. Abre **Configuración** (pulsa las teclas `Windows + I`).
2. Ve a **Sistema** > **Recuperación**.
3. En la opción **Restablecer este equipo**, haz clic en el botón **Restablecer el equipo**.
4. Elige una opción:
* **Mantener mis archivos:** Borra apps y configuraciones, pero conserva tus archivos personales.
* **Quitar todo:** (Recomendado para dejarlo 100% como el primer día). Borra absolutamente todo y reinstala Windows limpio.


5. Elige **Descarga en la nube** (descarga un Windows limpio y actualizado) o **Reinstalación local**.
6. Sigue los pasos y deja que el portátil haga su trabajo (tardará un rato y se reiniciará varias veces).

---

## Opción 2: Limpieza profunda (Sin borrar tus aplicaciones)

Si prefieres no reinstalar todo desde cero, puedes liberar espacio crítico y agilizar el sistema con estos tres pasos esenciales:

### 1. El Sensor de Almacenamiento (El mejor aliado en Windows 11)

Windows 11 tiene una herramienta fantástica para borrar gigabytes de basura automáticamente.

* Ve a **Configuración** > **Sistema** > **Almacenamiento**.
* Activa el **Sensor de almacenamiento** para que limpie archivos temporales por sí solo.
* Haz clic en **Archivos temporales**. Espera a que escanee y verás cuánto espacio ocupan las actualizaciones antiguas de Windows (puedes borrarlas sin miedo), las descargas y la papelera. Marca las casillas y dale a **Quitar archivos**.

### 2. Desactivar programas de inicio automático

Muchos programas se arrancan solos al encender el portátil, consumiendo RAM y CPU en segundo plano desde el primer segundo.

* Pulsa `Ctrl + Mayús + Esc` para abrir el **Administrador de tareas**.
* En el menú de la izquierda, haz clic en el icono de **Aplicaciones de arranque** (parece un velocímetro o una lista).
* Revisa la lista y **Deshabilita** todo lo que no sea imprescindible (como Spotify, Teams, launchers de juegos o navegadores). No te preocupes, el programa no se borra, solo se abrirá cuando tú lo decidas.

### 3. Desinstalar lo que ya no uses

* Ve a **Configuración** > **Aplicaciones** > **Aplicaciones instaladas**.
* Ordena la lista por **Tamaño** (de mayor a menor) y elimina esos programas o herramientas pesadas que instalaste una vez y no has vuelto a abrir.

---

Si después de vaciar el disco o restablecerlo notas que el sistema sigue sin volar, podría ser un buen momento para revisar si el disco duro que tiene es un **SSD** (los rápidos) o un **HDD** tradicional (los antiguos mecánicos, que con Windows 11 sufren muchísimo). Pero empieza por el restablecimiento o la limpieza de archivos temporales; el 90% de las veces, el problema es simplemente que el sistema se ha quedado sin "aire" para respirar debido a la falta de espacio.


----
```
- En la opción 1, si lo hago me quedaré sin licencia, que estará en el ordenador

```

¡Para nada! Puedes estar completamente tranquilo con esto: **no vas a perder tu licencia de Windows 11**.

El sistema de licencias de Microsoft ha cambiado mucho y ya no funciona como hace años, cuando necesitabas apuntar una clave en un papel o buscar la pegatina debajo del portátil.

Hoy en día, tu licencia está totalmente segura por dos razones:

### 1. Inyección digital en la placa base (Licencia OEM)

Al ser un portátil que ya venía con Windows, la clave de producto está **grabada digitalmente en el hardware** (en la BIOS/UEFI de la placa base). Cuando restableces el ordenador o reinstalas Windows desde cero, el propio instalador lee esa clave automáticamente en segundo plano. No te va a pedir ningún código y se activará solo en cuanto detecte conexión a internet.

### 2. Vinculación a tu cuenta de Microsoft

Si inicias sesión en el portátil con un correo electrónico (de Outlook, Hotmail, etc.), tu licencia de Windows 11 también se vincula a tu **identidad digital**. Al volver a configurar el equipo tras el formateo y poner tu cuenta, Microsoft reconocerá que ese ordenador ya tenía una licencia válida y se activará de inmediato.

---

### Un consejo por si quieres total tranquilidad

Si quieres quedarte 100% seguro antes de darle al botón de restablecer, puedes comprobar que todo está en orden haciendo esto:

1. Ve a **Configuración** (`Windows + I`).
2. Entra en **Sistema** > **Activación**.
3. Verás un apartado que dice **Estado de la activación**. Si despliegas la flecha, debería poner algo como: *"Windows está activado con una licencia digital"* o *"Windows está activado con una licencia digital vinculada a tu cuenta de Microsoft"*.

Si ves ese mensaje, tienes luz verde absoluta. Puedes borrar el ordenador por completo con la **Opción 1** sin ningún miedo; volverá a arrancar activado y legal como el primer día.



----
```
- Entonces, cuando "Elige Descarga en la nube (descarga un Windows limpio y actualizado) o Reinstalación local.", ya luego coge la licencia almacenada en la BIOS?

```

¡Exactamente! Lo has entendido a la perfección. Da igual cuál de las dos opciones elijas, el proceso con la licencia es el mismo:

* **Si eliges Descarga en la nube:** El ordenador se baja los archivos de instalación limpios y más recientes directamente de los servidores de Microsoft.
* **Si eliges Reinstalación local:** El ordenador utiliza los archivos que ya tiene guardados en una partición interna oculta para reconstruir el sistema.

En ambos casos, en cuanto el proceso termina y Windows arranca por primera vez, el sistema operativo **hace una consulta a la BIOS/UEFI de tu portátil**, lee la clave digital que viene de fábrica y se activa automáticamente en segundo plano. No notarás nada, simplemente verás que está activado.

### Un pequeño consejo para el proceso:

Si te decantas por la **Descarga en la nube** (que suele ser la más limpia porque te ahorra descargar actualizaciones pesadas después), asegúrate de tener el portátil **conectado al cargador** y preferiblemente cerca del router (o por cable) para que baje los archivos rápido y sin cortes.

Una vez que empiece, puedes desentenderte por completo. El ordenador se reiniciará varias veces y, cuando termine, te saludará con la pantalla de configuración inicial, exactamente igual que cuando lo sacaste de la caja por primera vez.


----
```
- En España, para hacer teletrabajo, las empresas tienen la obligación de darte un portatil y un móvil?

```

En España, la respuesta corta es **sí, la empresa está obligada a poner los medios necesarios, pero la ley no nombra específicamente un "móvil" o un "portátil"**, sino que habla de "equipos, herramientas y medios vinculados al desarrollo de la actividad".

La normativa clave es la **Ley 10/2021 de Trabajo a Distancia** (que se aplica cuando teletrabajas al menos el 30% de tu jornada en un periodo de tres meses, es decir, unos 2 días a la semana). Esta ley deja muy claras las reglas del juego:

### 1. Prohibición de usar tus equipos personales (El principio BYOD)

La ley **prohíbe expresamente** que la empresa te obligue a usar tu propio ordenador o tu propio teléfono para trabajar. Tampoco te pueden exigir que instales programas corporativos (como la propia VPN de la que hablábamos antes, aplicaciones de fichar o Teams) en tus dispositivos privados. Tu ordenador y tu móvil personales pertenecen a tu ámbito de intimidad.

### 2. Obligación de proporcionar las herramientas

La empresa debe encargarse de aportar, instalar y mantener todo lo que te haga falta para rendir desde casa.

* Si para tu puesto necesitas redactar informes, programar o conectarte a la red interna, te tienen que dar un **ordenador** (portátil o de sobremesa).
* Si tu puesto requiere hacer o recibir llamadas de clientes, coordinarte con el equipo por voz o estar localizable, te tienen que dar un **teléfono de empresa**. Si tu trabajo no requiere llamadas y te comunicas 100% por el chat del ordenador, la empresa no tendría obligación de darte un terminal físico móvil.

### 3. Compensación de gastos

El teletrabajo no te puede costar dinero. Aparte de los equipos físicos, la empresa tiene que sufragar o compensar los gastos derivados de trabajar en casa (la parte proporcional de **internet y luz**).

> La cantidad exacta o cómo se paga no viene fijada por ley, sino que **se regula a través del Convenio Colectivo** de tu sector o mediante un acuerdo firmado directamente contigo (suele ser un plus mensual en la nómina, por ejemplo, de 20 € a 45 € al mes).

### Todo debe quedar por escrito

Antes de empezar a teletrabajar, tienes que firmar obligatoriamente un **Acuerdo de Trabajo a Distancia**. En ese documento debe aparecer un **inventario detallado** con todo lo que la empresa te entrega (el portátil con su número de serie, ratón, pantalla si hiciera falta, móvil...) y cómo te van a pagar los gastos de luz e internet.

Así que, si te proponen teletrabajar de forma regular, no tienes por qué sacrificar el almacenamiento ni el rendimiento de tu portátil personal; es la empresa la que debe proporcionarte tu herramienta de trabajo limpia y configurada.