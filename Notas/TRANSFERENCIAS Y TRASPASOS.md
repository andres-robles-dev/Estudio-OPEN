### Consultar una transferencia recibida o enviada

Ruta: ==🔵`Picaso → Más Aplicaciones → Transferencias SEPA → Gestión de Pagos`==

Dentro de la herramienta:

1. Seleccionar recibida o enviada.
    
2. Introducir el número de cuenta sin dígito de control.
    
3. Localizar la transferencia.
    
4. Consultar su detalle. 


### Solicitar la retrocesión de una transferencia

Destino de la gestión: ==🔵`Picaso → Alta Nuevo GAP → Transaccional → Transferencias Nacionales`== 

Sirve para: solicitar la devolución de una transferencia en los supuestos admitidos por el procedimiento. No garantiza la recuperación del dinero. 


## 2. MODALIDADES, PUNTOS CLAVE Y CONDICIONES

### Traspaso entre cuentas

- Movimiento entre cuentas del mismo titular en Openbank.
    
- Disponible entre Cuenta Corriente y cuentas de ahorro.
    
- Inmediato cuando ambas cuentas están en euros.
    
- Los traspasos entre cuentas de distinta divisa requieren cambio de moneda y pueden tener otros plazos.
    

### Transferencia interna

- Entre cuentas de Openbank.
    
- El beneficiario puede ser otra persona.
    
- Recepción inmediata cuando ambas cuentas están en euros.
    

### Transferencia externa ordinaria

- Entre Openbank y otra entidad bancaria.
    
- Habitualmente llega el siguiente día hábil.
    
- El manual indica un corte a las 21:30 para el cómputo del plazo.
    
- Transferencias ordinarias en euros: gratuitas según condiciones del catálogo.
    

### Transferencia inmediata

- Dinero disponible en la cuenta de destino en tiempo real, si ambas entidades admiten la operación.
    
- Disponible en el ámbito SEPA.
    
- Comisión: 0 €.
    
- No permite programación periódica.
    

### Transferencia OMF — Banco de España

- Transferencia en el mismo día, antes de las 17:00 según el manual.
    
- Comisión: 0 €.
    
- Requiere que el cliente sea residente.
    

### Transferencia nómina

- La emite la empresa mediante una identificación interbancaria específica.
    
- Si no se identifica correctamente, se recibe como transferencia ordinaria.
    

### Límites y seguridad

- Web/app: límite diario de 50.000 € según manual.
    
- Teléfono: sin límite diario general indicado, sujeto a controles y autorizaciones.
    
- Transferencia por Picaso: N1 + N2 + OTP, para cualquier importe.
    
- Web/app: N1 + OTP; pueden exigirse verificaciones adicionales. 


## 3. GESTIONES Y RELACIÓN CON LAS RUTAS

| Gestión                               | Qué haces / ruta                                          |
| ------------------------------------- | --------------------------------------------------------- |
| Consultar transferencia emitida       | Más Aplicaciones → Transferencias SEPA → Gestión de Pagos |
| Consultar transferencia recibida      | Más Aplicaciones → Transferencias SEPA → Gestión de Pagos |
| Solicitar retrocesión                 | GAP → Transaccional → Transferencias Nacionales           |
| Emitir transferencia ordinaria        | Se gestiona por Picaso; ruta exacta no documentada        |
| Emitir transferencia inmediata        | Se gestiona por Picaso; ruta exacta no documentada        |
| Realizar traspaso entre cuentas       | Gestión disponible; ruta exacta no documentada            |
| Programar transferencia periódica     | Gestión disponible; ruta exacta no documentada            |
| Consultar cuentas de origen y destino | N1 → Posición Global                                      |
|                                       |                                                           |

-----
-----
-----

# TRANSFERENCIAS Y TRASPASOS — RESUMEN DE ADICIONALES

Operativa Bancaria v.17 · Procedimientos Simples v.5 · Uso interno

## 1. Seguridad para emitir transferencias

|Canal|Seguridad requerida|
|---|---|
|Web/App|N1 + OTP|
|Web/App superior a 10.000 €|N1 + N2 + OTP, según manual|
|Picaso, cualquier importe|N1 + N2 + OTP|

Antes de emitir, aplicar las medidas de seguridad del artículo «Árbol de decisión – Procedimientos críticos» en KB. No basta con autenticar al cliente.


## 2. Protocolo de fugas de pasivo

Una fuga de pasivo ocurre cuando un cliente quiere trasladar dinero de Openbank a otra entidad.

|Importe|Actuación|
|---|---|
|Menos de 3.000 €|Emitir con seguridad habitual. Sin FORMS|
|De 3.000 € a 10.000 €|Sondeo del motivo. Sin FORMS|
|De 10.000 € a 100.000 €|Aplicar protocolo y registrar en FORMS|
|Más de 100.000 €|FORMS + autorización de coordinadores|

Importante: si es para ahorro o inversión, se intenta retener ofreciendo alternativas adecuadas. Para consumo, vivienda, coche u otros motivos, no se aplica el ofrecimiento de retención de inversión.

El manual presenta diferencias de redacción en los límites exactos de 10.000 € y 100.000 €; ante un importe justo en el umbral, confirmar la matriz vigente en KB.


## 3. Retrocesión de transferencias

¿Qué es? Solicitar que una transferencia enviada vuelva a la cuenta de origen.

Ruta / destino: `GAP → Transaccional → Transferencias Nacionales`

Según el manual, se solicita en casos de estafa, fraude de transferencias o error tecnológico.

El banco de destino solicita la devolución y generalmente necesita la aceptación del beneficiario. La recuperación no está garantizada.

Operativa Bancaria 10 2026 v.17.docx

## 4. Transferencias internacionales

|Concepto|Condición del manual|
|---|---|
|SEPA|Zona de pagos en euros; transferencias SEPA gratuitas|
|SWIFT|Sistema de transferencias internacionales fuera de SEPA o en otras divisas|
|BIC de Openbank|`OPENESMMXXX`|
|Comisión de emisión Openbank|0 €|
|Gastos de bancos corresponsales|Pueden aplicarse; el manual indica aproximadamente 0–20 €|
|Tipo de cambio|Mesa de Tesorería del Banco Santander|

Para transferencias internacionales, comprobar beneficiario, IBAN, BIC/SWIFT, importe, moneda y gastos aplicables. Las transferencias SWIFT ya gestionadas no se anulan directamente: solo cabe solicitar retrocesión.


## 5. Situaciones especiales en llamadas

|Cliente dice…|Qué debes comprobar|
|---|---|
|«Mi transferencia todavía no llega»|Tipo, fecha de emisión, horario y estado en Gestión de Pagos|
|«Me equivoqué al enviarla»|Supuesto concreto y si procede solicitar retrocesión|
|«Quiero enviar 50.000 €»|Canal, seguridad y protocolo de fugas|
|«Necesito que llegue hoy»|Transferencia inmediata u OMF, según condiciones|
|«Quiero una transferencia internacional»|IBAN, BIC, divisa, gastos y condiciones SWIFT|
|«Quiero programar una inmediata»|El manual no permite inmediatas periódicas|

## 6. Para memorizar

Las tres claves del tema:

Seguridad: N1 + N2 + OTP en transferencias por Picaso.

Fugas: a partir del tramo de 10.000 €, revisar FORMS y el protocolo; más de 100.000 €, coordinadores.

Retrocesión: GAP a Transaccional – Transferencias Nacionales, únicamente si corresponde al supuesto permitido.