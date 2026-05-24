# Simulacro: ¿es phishing?

**Phishing** es cuando alguien les manda un mensaje haciéndose pasar por otra persona o institución (el banco, ANSES, Correo Argentino, hasta un familiar) para robarles datos, plata o una cuenta.

En esta página hay 8 ejemplos basados en estafas reales que circulan en Argentina. Léanlos uno por uno, **piensen primero si es phishing o real**, y después abran el desplegable para ver la respuesta y las banderas rojas.

```{tip}
No hay apuro. Esta página no es una clase de una hora: es para practicar de a poco, una vez por semana, cuando tengan ganas. Cuanto más practiquen, más fácil les va a salir detectarlas en la vida real.
```

## Ejemplo 1: WhatsApp de un "familiar"

> *De un número desconocido:*
>
> "Hola ma, soy yo. Se me rompió el celular y estoy usando este número nuevo. Necesito que me hagas una transferencia urgente al CBU que te paso ahora. Después te explico bien."

:::{dropdown} ¿Phishing o real? Tocá para ver la respuesta
**PHISHING.** Esta es una de las estafas más comunes en Argentina hoy.

**Banderas rojas:**
- Número desconocido que dice ser un familiar.
- Urgencia: "necesito ayuda ya".
- Pedido de transferencia a un CBU nuevo.
- "Después te explico" corta cualquier intento de verificar.

**Qué hacer:** llamar al **número viejo** (el que ya tenían guardado). Si no atiende, llamar a otro familiar para confirmar. **Nunca transferir sin verificar por otro canal.**
:::

## Ejemplo 2: Mail del "banco"

> **De:** seguridad@galicia-online-seguridad.com
> **Asunto:** URGENTE: Verifique su cuenta en 24 horas
>
> Estimado cliente,
>
> Detectamos un acceso sospechoso a su cuenta del Banco Galicia. Por su seguridad, su cuenta será suspendida en 24 horas si no verifica sus datos.
>
> Haga clic aquí para verificar: http://galicia-online-seguridad.com/login
>
> Equipo de Seguridad, Banco Galicia

:::{dropdown} ¿Phishing o real?
**PHISHING.**

**Banderas rojas:**
- Urgencia artificial ("24 horas o suspendemos la cuenta").
- Link sospechoso: el banco real es `bancogalicia.com.ar`, no `galicia-online-seguridad.com`. Cualquier dominio raro es señal de alarma.
- Los bancos **nunca** piden verificar la cuenta por mail con un link.
- "Estimado cliente": el banco sabe el nombre, no usa saludos genéricos.

**Qué hacer:** NO tocar el link. Si quieren chequear, entrar al sitio del banco **escribiendo la dirección a mano** en el navegador, o llamar al teléfono que figura atrás de la tarjeta.
:::

## Ejemplo 3: SMS de Correo Argentino

> **SMS:** CORREO ARGENTINO: Su paquete N°847291 está retenido en aduana. Abone $1.890 para liberarlo: http://corarg.envios-pago.net

:::{dropdown} ¿Phishing o real?
**PHISHING.**

**Banderas rojas:**
- Dominio raro: `corarg.envios-pago.net` no es el sitio oficial (`correoargentino.com.ar`).
- Pago bajo presión, monto chico para que no sospechen.
- Si no estaban esperando un paquete, ¿por qué tendrían algo retenido?

**Qué hacer:** si esperan un paquete, entrar al sitio oficial del Correo y rastrearlo con el número de envío. Si no esperaban nada, ignorar y borrar.
:::

## Ejemplo 4: Mail de Google

> **De:** no-reply@accounts.google.com
> **Asunto:** Se detectó un nuevo inicio de sesión en tu cuenta de Google
>
> Hola María,
>
> Detectamos un inicio de sesión en tu cuenta desde un dispositivo nuevo:
>
> - Dispositivo: iPhone 13
> - Ubicación: Buenos Aires, Argentina
> - Hora: 14 de mayo, 10:35
>
> Si fuiste vos, podés ignorar este mensaje. Si no fuiste vos, revisá tu actividad: [Revisar actividad]
>
> El equipo de Google

:::{dropdown} ¿Phishing o real?
**REAL** (casi siempre).

**Por qué parece legítimo:**
- Saluda con el nombre real.
- Da información específica (dispositivo, ubicación, hora).
- No pide plata ni contraseña.
- No tiene urgencia exagerada: dice "si fuiste vos, ignoralo".
- El remitente es `@accounts.google.com`.

**Pero ojo, aun así, la mejor manera de revisar la actividad es ir a `myaccount.google.com` directamente desde el navegador**, no tocando el link del mail. Eso vale para cualquier alerta de seguridad: nunca depender del link del mail aunque parezca real.

**Moraleja:** que algo sea real no significa que tengan que actuar a través del link. Siempre prefieran ir al sitio oficial a mano.
:::

## Ejemplo 5: WhatsApp de "ANSES"

> *De: +54 9 11 5xxx-xxxx (número desconocido)*
>
> "ANSES: Su jubilación está suspendida por falta de actualización de datos. Para reactivarla, complete sus datos personales y CBU acá: http://anses-tramites.online/actualizar"

:::{dropdown} ¿Phishing o real?
**PHISHING.**

**Banderas rojas:**
- ANSES no escribe por WhatsApp. Punto.
- Dominio falso: el real es `anses.gob.ar`.
- Piden CBU: con eso pueden vaciar la cuenta.
- Amenaza con suspender el cobro para asustar.

**Qué hacer:** ANSES nunca pide datos por WhatsApp ni por mail. Cualquier trámite real se hace en el sitio oficial (anses.gob.ar) o en una sucursal con turno previo. Si tienen dudas, llamar al 130.
:::

## Ejemplo 6: Mail de Mercado Pago

> **De:** notificaciones@mercadopago-cobros.com
> **Asunto:** Recibiste un pago de $45.000
>
> ¡Felicitaciones! María Pérez te transfirió $45.000.
>
> Para acreditar el dinero en tu cuenta, confirmá tus datos acá: **[Acreditar pago]**

:::{dropdown} ¿Phishing o real?
**PHISHING.**

**Banderas rojas:**
- Si alguien transfiere por Mercado Pago, el dinero se acredita solo. **No hay que "confirmar" nada.**
- Dominio sospechoso (`mercadopago-cobros.com` no es el real, que es `mercadopago.com.ar`).
- Promesa de plata gratis o inesperada.

**Qué hacer:** abrir la app de Mercado Pago directamente y ver si el pago figura en el saldo. Si no figura, no existió.
:::

## Ejemplo 7: WhatsApp con un código de verificación

> *Mensaje de un contacto que dice ser un amigo:*
>
> "Hola, te mando esto desde mi otro número. Mercado Libre me mandó por error un código a tu celular, ¿me lo pasás? Es el 847291."

:::{dropdown} ¿Phishing o real?
**PHISHING.** Esta estafa sirve para robarles la cuenta de Mercado Libre (o de WhatsApp, según la versión).

**Banderas rojas:**
- Les piden un código que llegó a SU celular.
- Cualquier código que les llega a ustedes es **suyo**. Nadie debería pedírselos.

**Qué hacer:** NO mandar el código. Bloquear el contacto.

**Regla universal:** los códigos que les llegan por SMS o WhatsApp para entrar a una cuenta (bancos, WhatsApp, Mercado Libre, Gmail) son personales. **Nunca se comparten con nadie**, ni siquiera con un familiar que parezca pedirlo "por error".
:::

## Ejemplo 8: Mail "Edenor"

> **De:** facturacion@edenor-pagos.serv.ar
> **Asunto:** ÚLTIMO AVISO: Vencimiento de factura
>
> Su factura de luz de $12.450 vence HOY. Si no abona antes de las 23:59, su servicio será suspendido sin previo aviso.
>
> Pagar ahora: http://edenor-pagos.serv.ar/factura

:::{dropdown} ¿Phishing o real?
**PHISHING.**

**Banderas rojas:**
- Urgencia artificial ("HOY", "ÚLTIMO AVISO").
- Dominio raro (`edenor-pagos.serv.ar` no es `edenor.com`).
- Las empresas de servicios no cortan la luz por una factura vencida sin múltiples avisos previos.

**Qué hacer:** si dudan, entrar al sitio oficial de la empresa escribiendo la dirección en el navegador, o pagar como siempre lo hacen (Pago Mis Cuentas, débito automático, sucursal).
:::

## Checklist rápido: ¿es phishing?

Si la respuesta a **cualquiera** de estas es SÍ, sospechen:

- [ ] ¿Me piden plata, contraseña, código o CBU?
- [ ] ¿Hay urgencia exagerada ("ya", "24 horas", "último aviso", "se suspende")?
- [ ] ¿El link es raro y no es el sitio oficial?
- [ ] ¿Viene de un número o mail desconocido?
- [ ] ¿Me ofrecen algo gratis, un premio, o plata que no esperaba?
- [ ] ¿La forma de hablar es genérica ("estimado cliente") en vez de usar mi nombre?
- [ ] ¿Es algo que no esperaba (un paquete que no pedí, un pago de alguien que no conozco)?

```{important}
**Regla universal:** cuando duden, no toquen nada. Cierren el mensaje y vayan al sitio oficial de la institución (banco, ANSES, Correo) escribiendo la dirección a mano en el navegador. Si no es phishing, ahí van a poder hacer el trámite igual. Si es phishing, se salvaron.
```

## ¿Y si caí?

Si tocaron un link sospechoso y metieron datos, **no es el fin del mundo**. Estas estafas están diseñadas por gente que sabe manipular y a cualquiera le puede pasar. Lo importante es reaccionar rápido:

1. **Cambien la contraseña** del servicio afectado (banco, mail, WhatsApp) desde otro dispositivo si pueden.
2. Si fue del **banco**: llamen al banco al número que figura atrás de la tarjeta para bloquear la cuenta o las tarjetas.
3. Si fue de **WhatsApp**: vayan a Ajustes → Cuenta → Verificación en dos pasos y activen el PIN. Si perdieron el acceso, escriban a `support@whatsapp.com`.
4. Si dieron el **CBU**: avisen al banco y pidan bloquear movimientos sospechosos.
5. **Avísenme.** Sin vergüenza. Cuanto antes me digan, más rápido podemos minimizar el daño.

```{tip}
**Anoten cada estafa que reciban**, aunque no caigan, en un documento o en una nota del celular. Sirve para que cuando vuelva a aparecer una parecida la reconozcan al instante.
```

---

➡️ Para cerrar el curso, vayan al [Machete general](recursos.md): todo lo importante en una sola página.
