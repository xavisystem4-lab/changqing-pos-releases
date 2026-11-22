# Chongqing POS 0.9.12 — Propinas

- Cobro con tarjeta: el cargo sugerido es el total de la cuenta y se puede cambiar. «¿El cliente dejó propina?» con «Sin propina» o «Sí, dejó propina» (monto o 10/15/20 %). Si se cobra de más en la tarjeta, la diferencia se toma como propina.
- Toda propina pregunta, antes de cerrar el cobro, a quién le toca: un mesero o «Directo a caja». No deja confirmar sin elegir; «Volver» regresa al cobro sin perder los pagos.
- Cuentas cerradas: columna «Propina» con a quién se asignó; el detalle muestra con qué se pagó. «✎ Propina» corrige la asignación con PIN de supervisor y queda registrado quién, cuándo y de quién a quién.
- Nuevo «💰 Propinas» (en Cuentas cerradas y en Corte): acumulado por mesero y directo a caja, en tarjeta y en efectivo, por turno actual, hoy o todas; con sus folios.
- Corte de caja: sección de propinas separada de las ventas, desglosada por mesero, caja y medio de pago. «Efectivo a entregar» ya no incluye propinas; «Total en cajón» sí incluye las propinas en efectivo.
