# Clase 6: Seguridad digital

⏱️ **Duración:** 1 hora
💻📱 **Dispositivo:** celular y computadora

## Para qué les sirve

Hasta acá aprendimos a usar las herramientas. Esta clase es para usarlas con tranquilidad: saber distinguir cuándo algo es real y cuándo es trucho, y poner candados extra para que aunque alguien intente robarles datos, no pueda.

Es la clase más importante del curso desde el lado de la seguridad. La mayoría de las estafas digitales caen apenas la persona conoce dos o tres trucos básicos.

## Antes de empezar

- Celular y computadora.
- El **cuadernito de contraseñas** que vimos en clase 1 (lo van a actualizar acá).
- Saber sus contraseñas de Gmail y WhatsApp.

## Paso a paso

### 1. Cómo leer una dirección de internet (URL)

Una **URL** es la dirección de un sitio web. Ejemplos:

- `bancogalicia.com.ar`
- `google.com`
- `anses.gob.ar`

Aprender a leerlas bien es **lo más importante de toda esta clase**, porque las estafas usan URLs que **se parecen** a las reales pero no lo son.

**Truco para leer una URL:**

La parte que importa está justo **antes del primer `/`**. Eso es **el dueño real del sitio**.

| URL completa | Dueño real |
|---|---|
| `https://bancogalicia.com.ar/login` | bancogalicia.com.ar ✅ |
| `https://galicia.fake-site.com/login` | fake-site.com ❌ |
| `https://anses.gob.ar/jubilados` | anses.gob.ar ✅ |
| `https://anses-tramites.online/actualizar` | anses-tramites.online ❌ |

Fíjense en el segundo y cuarto caso: el nombre conocido ("galicia", "anses") aparece **al principio para confundir**, pero el dueño real (el último nombre antes del `/`) es otro.

**Otras señales de URLs sospechosas:**

- Errores chiquitos: `gallicia.com` (doble L), `bancogalícia.com` (tilde rara), `merca-libre.com` (con guion).
- Terminaciones raras: `.online`, `.xyz`, `.click`, `.info`. No están prohibidas, pero son menos habituales en sitios oficiales.
- Subdominios larguísimos: `seguridad-banco-galicia-actualizacion.com`.

```{tip}
Los sitios oficiales del gobierno argentino terminan en **`.gob.ar`**. Cualquier "anses", "afip" o "ministerio" con otra terminación es falso.
```

### 2. El candadito 🔒 y la "s" de https

Al lado de la dirección, casi siempre arriba a la izquierda, ven un **candadito** 🔒. Y la dirección empieza con `https://` (con **s**) en vez de `http://`.

**Qué significa el candadito:** la conexión está **encriptada**. Lo que mandan al sitio (contraseña, datos personales) no se puede leer si alguien intercepta el tráfico en el camino. Es como hablar en un cuarto cerrado en vez de gritar en el balcón.

```{warning}
**El candadito NO garantiza que el sitio sea legítimo.**

Solo garantiza que la conexión es privada. **Un sitio trucho también puede tener candadito.** Lo único que el candadito asegura es que nadie de afuera ve lo que mandan, pero los datos llegan igual al estafador si el sitio es falso.
```

O sea: el candadito es **necesario pero no suficiente**. Si no tiene candadito, no entren. Si tiene candadito, igual lean la URL completa.

### 3. Cuando el navegador les avisa que algo anda mal

A veces Chrome (u otro navegador) les muestra un cartel **rojo o naranja** con mensajes como:

- *"Tu conexión no es privada"*
- *"Atención: posible sitio engañoso"*
- *"Conexión no segura"*

**Si aparece ese cartel: cierren la pestaña. No lo ignoren.**

El navegador detecta cosas que ustedes no pueden ver a simple vista (certificados vencidos, sitios reportados como estafas, etc.). Confíen en el aviso.

```{warning}
Algunos carteles tienen un botón "Avanzar de todos modos" o "Continuar a sitio". **No lo toquen.** No es para gente común, es para programadores que están probando algo y saben lo que hacen.
```

### 4. La regla de oro: para datos importantes, dirección a mano

Para entrar al **banco**, a **ANSES**, al **mail**, o a **cualquier lugar donde van a meter contraseña o datos sensibles**:

1. **No usen links** que les llegan por mail, SMS o WhatsApp.
2. **Escriban la dirección a mano** en el navegador (`bancogalicia.com.ar`).
3. **O usen un favorito** que ustedes mismos hayan guardado.

¿Por qué? Porque los links de mail y WhatsApp son el vehículo principal del phishing. Aunque el mensaje parezca real, si tocan el link pueden terminar en un sitio falso idéntico al verdadero.

**Cómo guardar un favorito en Chrome** (lo hacen una vez y queda):

1. Entren al sitio real (ej: `bancogalicia.com.ar`).
2. Toquen la **estrellita ⭐** que está al lado de la dirección, arriba.
3. Le ponen un nombre fácil ("Banco") y guardan.

A partir de ahí, abrir el banco es un toque al favorito, no escribir nada.

### 5. Quiz rápido: ¿cuál es la URL real?

Practiquen. Para cada par, **piensen primero** cuál es el sitio oficial y cuál el falso, y después abran la respuesta.

:::{dropdown} 🏦 ¿Cuál es Banco Galicia? `bancogalicia.com.ar/login` vs `galicia-seguridad.com/login`
**La real es `bancogalicia.com.ar`**.

`galicia-seguridad.com` tiene el nombre del banco al principio para confundir, pero el dueño del sitio es `galicia-seguridad.com`, no el banco.
:::

:::{dropdown} 🇦🇷 ¿Cuál es ANSES? `anses.gob.ar/jubilados` vs `anses-online.info/jubilados`
**La real es `anses.gob.ar`**.

Los sitios del gobierno argentino terminan en `.gob.ar`. Cualquier "anses" con otra terminación (`.com`, `.info`, `.online`) es falso.
:::

:::{dropdown} 📧 ¿Cuál es Gmail? `mail.google.com` vs `gmail-login.com`
**La real es `mail.google.com`**.

Gmail vive **bajo `google.com`**. Cualquier cosa que diga "gmail" pero no termine en `google.com` es trucho.
:::

:::{dropdown} 🛒 ¿Cuál es Mercado Libre? `mercadolibre.com.ar` vs `merca-libre.com.ar`
**La real es `mercadolibre.com.ar`** (todo junto, sin guion).
:::

:::{dropdown} 💳 ¿Cuál es Mercado Pago? `mercadopago.com.ar` vs `mercadopago-cobros.com`
**La real es `mercadopago.com.ar`**.

Cualquier cosa con guiones o agregados (`-cobros`, `-seguridad`, `-pagos`) es invento.
:::

### 6. Verificación en dos pasos (2FA): el cinturón de seguridad

La **verificación en dos pasos** (también llamada "2FA" o "doble factor") es como una **segunda cerradura** en la puerta de casa.

> Aunque alguien les robe la contraseña, no puede entrar a su cuenta porque también necesita un **código que solo llega al celular de ustedes**.

Es la mejor protección que hay. Y se activa una sola vez. Si activan **una sola cosa** de toda esta clase, que sea esto.

#### 6.1 Activar 2FA en WhatsApp

1. Abren WhatsApp.
2. Tocan los **tres puntitos** ⋮ arriba a la derecha → **Ajustes**.
3. Tocan **Cuenta** → **Verificación en dos pasos** → **Activar**.
4. Inventan un **PIN de 6 dígitos**. **No usen** fecha de nacimiento, 123456, ni números fáciles. Algo como `492817`.
5. **Anótenlo en el cuadernito de contraseñas.** Si lo pierden, no pueden recuperar WhatsApp fácil.
6. Agregan un **mail de respaldo** (su Gmail). Si alguna vez olvidan el PIN, les llega ahí cómo recuperarlo.
7. Confirman.

A partir de ahora, si alguien intenta instalar su WhatsApp en otro celular, le va a pedir el PIN. **Sin PIN, no entra.** Esto protege específicamente contra la estafa del "perdí el celu" que vimos en clase 1.

#### 6.2 Activar 2FA en Gmail

1. En la **computadora**, van a `myaccount.google.com`.
2. En el menú de la izquierda, eligen **Seguridad**.
3. Buscan **Verificación en dos pasos** y tocan **Activar**.
4. Confirman con la contraseña de Gmail.
5. Google les pide su **número de celular**. Lo escriben.
6. Les llega un código por SMS. Lo escriben donde dice.
7. Confirman.

A partir de ahora, cuando entren a Gmail desde un dispositivo nuevo (un celular distinto, otra compu), además de la contraseña les va a pedir un código que llega al celular.

```{tip}
**Para probar que funciona:** cierren sesión de Gmail (foto arriba a la derecha → Cerrar sesión) y vuelvan a entrar. Después de la contraseña debería pedirles el código del celular.
```

### 7. Pop-ups truchos: "su computadora está infectada"

A veces, navegando, aparece un cartel grande que dice algo así:

> ⚠️ **ATENCIÓN: SU COMPUTADORA TIENE 9 VIRUS**
>
> Llame YA al 0800-XXX-XXXX para limpiarla. Si no actúa ahora, sus archivos serán eliminados.

A veces con sonido de alarma. A veces el cartel no se deja cerrar.

**Esto es 100% estafa.** Su computadora **no está infectada**. Es solo una página web haciendo ruido para asustarlos y que llamen.

**Qué hacer:**

1. ❌ **NO llamar** al número.
2. ❌ **NO instalar** nada que les diga descargar.
3. ❌ **NO meter datos** ni tarjeta.
4. ✅ **Cerrar la pestaña** (la X en la pestañita arriba). Si la X no funciona, cerrar el navegador entero.
5. ✅ Si vuelve a aparecer cuando reabren el navegador, **reiniciar la computadora**.

```{important}
**Microsoft, Google, Apple y los bancos jamás llaman ni mandan pop-ups así.** Si una página dice "su computadora está infectada, llame al 0800", es estafa **sin excepción**.
```

### 8. WiFi público: cuándo importa

El WiFi "gratis" del café, el aeropuerto, el hospital o un shopping es cómodo pero **menos seguro** que el de su casa.

En una red pública, otras personas conectadas pueden, en teoría, espiar parte del tráfico. Para sitios normales (mirar el diario, buscar algo en Google, ver mapas) no es problema. Para datos sensibles, sí.

| Lo que hacen | WiFi público | WiFi de casa o datos móviles |
|---|---|---|
| Leer el diario, buscar en Google, mapas | ✅ OK | ✅ OK |
| Mandar mensajes por WhatsApp | ✅ OK | ✅ OK |
| Entrar al **banco**, hacer transferencias | ❌ Evitar | ✅ OK |
| Comprar online con tarjeta | ❌ Evitar | ✅ OK |
| Sitios con contraseña importante | ⚠️ Mejor no | ✅ OK |

**Si necesitan urgente hacer banking estando afuera de casa:** desconecten el WiFi público y usen **los datos móviles del celular**. Lo poco que gasten vale la pena.

## Ejercicios para hacer en clase

1. ✅ Leer 5 URLs y decir cuál es la real (lo hacemos juntos con el quiz del paso 5).
2. ✅ Buscar el candadito 🔒 en el navegador, en el sitio del banco.
3. ✅ Guardar 3 favoritos en Chrome: banco, ANSES, Gmail.
4. ✅ Activar verificación en dos pasos en **WhatsApp** y anotar el PIN.
5. ✅ Activar verificación en dos pasos en **Gmail**.
6. ✅ Cerrar sesión de Gmail y volver a entrar para comprobar que pide el código.

## 📝 Tarea para la semana

- [ ] **Día 1:** Cada vez que toquen un link, **mirar la URL primero** antes de tocar. Acostumbrarse a leer.
- [ ] **Día 2:** Hacer una lista en Google Docs de los sitios oficiales que más usan (banco, obra social, ANSES, ARCA, servicios) con sus URLs reales escritas.
- [ ] **Día 3:** Guardar esos sitios como favoritos en Chrome.
- [ ] **Día 4:** Buscar en el mail los últimos 10 mensajes que les pidieron "verificar cuenta" y borrarlos sin tocar nada.
- [ ] **Día 5:** Hacer el [Simulacro de phishing](simulacro-phishing.md) con los 8 ejemplos. Contarme cuántos acertaron.

## Si algo sale mal

**"Activé la verificación en dos pasos en WhatsApp y me pide el PIN cada vez que abro la app."**
: WhatsApp no debería pedirlo siempre, solo cada cierto tiempo o al instalar la app en un dispositivo nuevo. Si lo pide todo el tiempo, revisen Ajustes → Cuenta → Verificación en dos pasos y verifiquen la configuración.

**"Perdí el PIN de WhatsApp."**
: Si pusieron mail de respaldo, sigan los pasos para recuperarlo desde ese mail. Si no pusieron mail, hay que esperar **7 días** para resetearlo (es una medida de seguridad de WhatsApp).

**"Entré a un sitio y no veo el candadito."**
: Salgan inmediatamente. No metan datos. Avisenme.

**"El navegador me muestra un cartel rojo y no entiendo qué dice."**
: Cierren la pestaña. Sáquenme una captura y me preguntan antes de volver a intentar.

**"Toqué un link sin querer y se abrió algo raro."**
: Cierren la pestaña inmediatamente. Si pueden, cierren todo el navegador. Si metieron datos en el sitio que se abrió: cambien la contraseña del servicio afectado y avisenme.

**"Me llamó alguien diciendo que era de Microsoft / del banco / de ANSES."**
: Cortar. Llamar al sitio oficial usando el número que figura en la tarjeta o en el sitio oficial. Microsoft, los bancos y ANSES no llaman así.

---

➡️ **Próxima página:** [Simulacro de phishing](simulacro-phishing.md), donde practican con 8 ejemplos reales todo lo que vieron en esta clase.
