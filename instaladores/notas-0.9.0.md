# Chongqing POS 0.9.0 — Conector estable

- El Enlace Móvil guarda una copia del mapa de mesas, el menú, los meseros y las cuentas abiertas, y contesta a las tablets al instante (1–3 ms).
- Las tablets siguen funcionando aunque la caja esté ocupada imprimiendo, con una ventana abierta o recién reiniciada (la copia también se guarda en disco).
- Las comandas y cuentas pedidas desde la tablet llegan con su identificador: si la tablet reintenta por un corte de red, la caja no las duplica.
- Después de cada comanda la copia se actualiza antes de avisar a las tablets, así ven el cambio de inmediato.
