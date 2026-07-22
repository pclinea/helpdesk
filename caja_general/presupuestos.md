## **PRESUPUESTOS**

Sigue los pasos para la gestión de tus **Presupuestos** y pagos pendientes:

Un **Presupuesto** registra un gasto programado (arriendo, servicios, nómina, etc.): proveedor, concepto, valor y fecha de pago. Puedes verlos en **Calendario** o en **Lista**, registrar abonos en la pestaña **Pagos** y configurar pagos **recurrentes**. En el **Dashboard**, la card **Control de pagos** resume los presupuestos pendientes del mes activo.

<details><summary class="text-primary">1. Crear un Presupuesto</summary>
        <p>1.1 En la esquina inferior derecha, haz clic en el <b>Botón + Rojo</b>.</p>
        <p>1.2 Indica la <b>Fecha de vencimiento (pago)</b> y selecciona el proveedor en <b>Pagar a</b>.</p>
        <p>1.3 Haz clic en <b>Continuar</b>. El sistema guarda el encabezado (la fecha de registro se asigna automáticamente).</p>
        <p>1.4 En <b>Concepto</b>, busca un gasto existente (mínimo 3 caracteres) o créalo con el acceso rápido de gasto (+).</p>
        <p>1.5 Digita el <b>Valor</b> y haz clic en <b>Guardar</b>. Al guardar el concepto se habilitan las pestañas del documento.</p>
        <p>1.6 En la pestaña <b>Datos del presupuesto</b> puedes agregar <b>Observaciones</b>.</p>
        <p>1.7 En la pestaña <b>Pagos</b> puedes registrar un abono parcial o el pago total.</p>
        <p>1.8 Opcional: en la pestaña <b>Recurrente</b> configura si el gasto se repite (ver sección 5).</p>
        <p>*El presupuesto queda ubicado en el calendario según su <b>fecha de vencimiento</b>.</p>
        <p>*Solo se listan conceptos tipo <b>Gasto</b>.</p>
</details>

<details><summary class="text-primary">2. Vista Calendario</summary>
        <p>2.1 En la cabecera, selecciona la vista <b>Calendario</b>.</p>
        <p>2.2 Usa las flechas para cambiar de mes, o elige una fecha en el campo <b>Fecha</b>.</p>
        <p>2.3 Cada día muestra los presupuestos programados. Los colores indican el estado:</p>
        <p>• <b>Pendiente</b> — sin pagos</p>
        <p>• <b>Parcial</b> — con abonos</p>
        <p>• <b>Vencido</b> — saldo pendiente y fecha de pago ya pasó</p>
        <p>• <b>Pagado</b> — saldo en cero</p>
        <p>• <b>No laborable / Festivo</b> — según la configuración del calendario</p>
        <p>2.4 Haz clic sobre un presupuesto del calendario para abrirlo y editarlo o registrar pagos.</p>
</details>

<details><summary class="text-primary">3. Vista Lista</summary>
        <p>3.1 En la cabecera, selecciona la vista <b>Lista</b>.</p>
        <p>3.2 Consulta código, fecha, proveedor, concepto, total, pagado, saldo y estado.</p>
        <p>3.3 Haz clic derecho sobre un registro para <b>Editar</b>, <b>Imprimir</b> u otras opciones disponibles.</p>
</details>

<details><summary class="text-primary">4. Editar un Presupuesto</summary>
        <p>4.1 Ábrelo desde el calendario o haz clic derecho en la lista y selecciona <b>Editar</b>.</p>
        <p>4.2 El modal muestra las pestañas <b>Datos del presupuesto</b>, <b>Pagos</b> y <b>Recurrente</b> (esta última cuando ya hay documento y concepto).</p>
        <p>4.3 En <b>Datos</b> puedes modificar fecha de vencimiento, proveedor, concepto, valor u observaciones.</p>
        <p>4.4 Al hacer clic en el campo <b>Concepto</b>, el nombre y el valor <b>no se borran</b>. Solo se actualizan si eliges un gasto nuevo del desplegable después de buscar.</p>
        <p>4.5 Los cambios de encabezado se guardan al actualizar cada campo; el concepto se guarda con el botón <b>Guardar</b>.</p>
        <p>4.6 Si el presupuesto es origen de una serie con límites, al guardar la pestaña <b>Recurrente</b> se recalculan los documentos generados (ver sección 6).</p>
</details>

<details><summary class="text-primary">5. Configurar un Presupuesto Recurrente</summary>
        <p>5.1 Abre el presupuesto y ve a la pestaña <b>Recurrente</b>.</p>
        <p>5.2 Activa <b>¿Es recurrente?</b>.</p>
        <p>5.3 Selecciona la <b>Frecuencia</b> (las frecuencias se administran en <b>Administración → Frecuencias</b>).</p>
        <p>5.4 Indica la <b>Fecha de repetición</b> (fecha de pago / vencimiento). Por defecto se toma la <b>fecha de vencimiento del documento</b>.</p>
        <p>5.5 Opcional: activa <b>¿Limitar repeticiones?</b> e ingresa la cantidad (ej. 12).</p>
        <p>5.6 Opcional: activa <b>¿Tiene fecha de finalización?</b> e indica hasta cuándo se genera la serie.</p>
        <p>5.7 Haz clic en <b>Guardar</b>.</p>
        <p>*Con cantidad o fecha fin, se generan de una vez los presupuestos de la serie en el calendario.</p>
        <p>*Sin límites (sin cantidad ni fecha fin) puedes guardar la recurrencia aunque haya saldo. El siguiente presupuesto se crea automáticamente al <b>liquidar el saldo</b> y <b>cerrar el modal</b>, <b>copiando la configuración recurrente</b> para que la cadena continúe indefinidamente.</p>
        <p>*El presupuesto conserva su fecha de registro; las fechas de la serie se reflejan en el <b>vencimiento</b> (fecha de pago).</p>
</details>

<details><summary class="text-primary">6. Actualizar o recalcular una serie recurrente</summary>
        <p>6.1 <b>Con límites</b> (cantidad o fecha fin): abre el presupuesto <b>origen</b> de la serie (no un documento generado).</p>
        <p>6.2 En la pestaña <b>Recurrente</b>, modifica frecuencia, fechas, cantidad o fecha de finalización.</p>
        <p>6.3 Haz clic en <b>Guardar</b>.</p>
        <p>6.4 El sistema recalcula la serie:</p>
        <p>• Actualiza fechas, montos y conceptos de los documentos generados sin pagos.</p>
        <p>• Crea documentos faltantes si aumentan las repeticiones.</p>
        <p>• Anula los excedentes si disminuyen las repeticiones.</p>
        <p>6.5 Si algún documento generado ya tiene pagos, no se puede recalcular hasta anular o eliminar esos pagos.</p>
        <p>6.6 Para desactivar la recurrencia, apaga <b>¿Es recurrente?</b> y guarda: puedes eliminar los documentos generados sin pagos o conservarlos.</p>
        <p>*Con cantidad o fecha fin, los generados muestran la config en solo lectura (edita en el origen). Desde el aviso puedes abrir el presupuesto origen.</p>
        <p>*Sin límites, la configuración <b>se copia al documento generado</b>; al liquidarlo y cerrar, crea el siguiente y le pasa la misma config. El documento liquidado deja de ser el activo de la cadena.</p>
</details>

<details><summary class="text-primary">7. Registrar pagos o abonos</summary>
        <p>7.1 Abre el presupuesto.</p>
        <p>7.2 Ve a la pestaña <b>Pagos</b> (separada de Datos, como en otros documentos).</p>
        <p>7.3 Registra el abono o el pago total (forma de pago y subcuenta según tu caja). Puedes registrar varios pagos.</p>
        <p>7.4 El estado pasa a <b>Parcial</b> o <b>Pagado</b> según el saldo.</p>
        <p>7.5 En el calendario verás el color actualizado del evento.</p>
        <p>7.6 Si el presupuesto es <b>recurrente sin límite</b> y el saldo queda en <b>0</b>, al <b>cerrar el modal</b> se crea el siguiente con los mismos datos, la siguiente fecha de vencimiento y <b>la misma configuración recurrente</b>. Si aún hay saldo, la recurrencia se mantiene guardada pero no se crea el siguiente hasta liquidarlo.</p>
</details>

<details><summary class="text-primary">8. Crear un gasto rápido</summary>
        <p>8.1 Al crear o editar un presupuesto, si el concepto no existe, usa el icono <b>+</b> junto a Concepto / Gasto, o pulsa <b>Enter</b> cuando no haya coincidencias en la lista.</p>
        <p>8.2 Digita el <b>Nombre</b> y el <b>Valor</b> del gasto.</p>
        <p>8.3 Confirma: el gasto queda disponible como concepto y se carga en el presupuesto.</p>
</details>

<details><summary class="text-primary">9. Buscar un Presupuesto</summary>
        <p>9.1 Haz clic en el icono <b>Buscar</b> (Accesos Directos).</p>
        <p>9.2 Filtra por <b>Tercero</b> (proveedor) y/o <b>Concepto</b>.</p>
        <p>9.3 Visualiza el resultado en la vista Lista.</p>
        <p>9.4 Usa <b>Limpiar</b> para quitar los filtros.</p>
</details>

<details><summary class="text-primary">10. Control de pagos en el Dashboard</summary>
        <p>10.1 En el <b>Dashboard</b>, la card <b>Control de pagos</b> muestra un resumen del mes.</p>
        <p>10.2 <b>Presupuestos pendientes (mes)</b>: saldo pendiente de presupuestos con vencimiento en el <b>mes activo</b>. Haz clic en la etiqueta o el monto para ir a Presupuestos.</p>
        <p>10.3 <b>Cuentas por pagar</b>: saldo pendiente de CxP. Haz clic para abrir Cartera → Cuentas por pagar.</p>
        <p>10.4 <b>Total restante por pagar</b>: suma de presupuestos del mes + CxP.</p>
        <p>10.5 <b>Ingresos del mes</b> y <b>Pagos realizados del mes</b>: movimientos de caja del mes.</p>
        <p>10.6 <b>Saldo en caja (mes)</b>: ingresos − pagos realizados. Se cruza con el total restante para indicar si alcanza, sobra o falta.</p>
        <p>10.7 <b>Promedio diario a cubrir</b>: faltante dividido entre los días restantes del mes.</p>
</details>
