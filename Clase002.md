# Clase 2 - La Primera Barrera de Defensa: Contraseñas y Autenticación 🔑

¡Hola a todos! Bienvenidos a nuestra segunda clase. Hoy vamos a construir nuestra primera y más importante muralla de defensa en el mundo digital: las contraseñas. Una contraseña es como la llave de tu casa; no se la darías a cualquiera ni la dejarías debajo del felpudo.

Aprenderemos a crear llaves (contraseñas) que sean prácticamente imposibles de romper y añadiremos una "cerradura extra" para máxima seguridad.

## 1. El Arte de Crear Contraseñas Indescifrables 🕵️‍♂️

La mayoría de las personas usan contraseñas débiles y predecibles como "123456", "password" o el nombre de su mascota. Un ciberdelincuente puede adivinar estas contraseñas en segundos usando software especializado. Una contraseña segura es tu primera línea de defensa.

**¿Qué hace que una contraseña sea FUERTE?**

* **Longitud:** Olvídate de los 8 caracteres. Una contraseña segura debe tener **al menos 12 caracteres**. Cuanto más larga, más difícil es de descifrar.

* **Complejidad:** Debe ser una mezcla de:

  * Letras mayúsculas (A-Z)

  * Letras minúsculas (a-z)

  * Números (0-9)

  * Símbolos (!, @, #, $, %, &, \*)

* **Imprevisibilidad:** No debe contener información personal fácil de adivinar (tu nombre, fecha de nacimiento, el nombre de tu equipo de fútbol, etc.).

**Técnica de la Frase Secreta (Passphrase): ¡Fácil de recordar, difícil de adivinar!**

Recordar contraseñas como `tG8*pWq@9!z` es casi imposible. En su lugar, utiliza una frase que solo tú entiendas y conviértela.

* **Paso 1:** Elige una frase larga y personal.

  * Ejemplo: `¡Mi perro Toby se comió 3 zapatos en el 2021!`

* **Paso 2:** Transfórmala usando las primeras letras y reemplazando palabras.

  * Usa "MpTs" de `Mi perro Toby se`.

  * `comió` lo puedes dejar o cambiar por un número que se parezca.

  * Usa el número `3`.

  * Usa "z" de `zapatos`.

  * "en el" puedes representarlo con un símbolo como `@`.

  * Usa el año `2021`.

  * No olvides el signo de exclamación `!`.

* **Resultado Final:** `MpTs-c0mió3z@2021!`

Esta contraseña es extremadamente fuerte y, para ti, es mucho más fácil de recordar que una cadena de caracteres aleatorios.

## 2. Gestores de Contraseñas: Tu Bóveda Digital Segura 🔒

Tener una contraseña única y fuerte para cada servicio (correo, redes sociales, banco, etc.) es crucial. Si un servicio sufre una filtración de datos, los atacantes no podrán usar esa misma contraseña para acceder a tus otras cuentas.

Pero, ¿cómo recordar decenas de contraseñas complejas? La respuesta son los **gestores de contraseñas**.

* **¿Qué son?** Son aplicaciones seguras que crean, guardan y rellenan automáticamente tus contraseñas por ti.

* **¿Cómo funcionan?** Solo necesitas recordar UNA contraseña muy fuerte: la **contraseña maestra** para acceder a tu gestor. El gestor se encarga del resto.

* **Ejemplos populares:** Bitwarden (gratuito), 1Password, Dashlane, LastPass.

¡Usar un gestor de contraseñas es uno de los mejores hábitos de seguridad que puedes adoptar!

## 3. Autenticación de Dos Factores (2FA): La Cerradura Extra 📱

Imagina que un ladrón logra robar la llave de tu casa (tu contraseña). Si tienes una segunda cerradura que requiere una llave especial que solo tú posees, el ladrón seguirá sin poder entrar. Eso es exactamente lo que hace la Autenticación de Dos Factores (2FA) o Verificación en Dos Pasos.

El 2FA combina dos de tres cosas:

* **Algo que sabes** (tu contraseña).

* **Algo que tienes** (tu teléfono móvil, una llave USB de seguridad).

* **Algo que eres** (tu huella digital o tu rostro).

**¿Cómo funciona en la práctica?**

Cuando inicias sesión en una cuenta con 2FA activado:

1. Introduces tu nombre de usuario y contraseña (lo que sabes).

2. El servicio te pedirá un segundo código de verificación (lo que tienes).

Este código se puede generar de varias formas:

* **App de Autenticación (Recomendado):** Aplicaciones como **Google Authenticator**, **Microsoft Authenticator** o **Authy** generan un código numérico que cambia cada 30 segundos. Es muy seguro.

* **Mensaje de texto (SMS):** Recibes un código en tu teléfono. Es seguro, pero ligeramente menos que una app.

* **Llave de seguridad física (FIDO2):** Un pequeño dispositivo USB que conectas a tu ordenador para verificar tu identidad. Es el método más seguro.

¡Activa el 2FA en todas tus cuentas importantes (correo electrónico, redes sociales, cuentas bancarias)!

## Resumen de la Clase y Tareas: ✅

* Crea contraseñas largas y complejas usando la técnica de la frase secreta.

* Utiliza una contraseña diferente para cada sitio web o servicio.

* Considera usar un gestor de contraseñas para administrar todas tus claves de forma segura.

* Activa la Autenticación de Dos Factores (2FA) en todas tus cuentas posibles, empezando por tu correo electrónico principal.

Ahora estás listo para poner a prueba tus conocimientos en la evaluación de esta clase. ¡Adelante!