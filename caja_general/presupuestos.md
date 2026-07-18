## **PRESUPUESTOS**

Sigue los pasos para la gestión de tus **Presupuestos** y pagos pendientes:

Un **Presupuesto** registra un gasto programado (arriendo, servicios, nómina, etc.): proveedor, concepto, valor y fecha de pago. Puedes verlos en **Calendario** o en **Lista**, registrar abonos y configurar pagos **recurrentes**.

<details><summary class="text-primary">1. Crear un Presupuesto</summary>
        <p>1.1 En la esquina inferior derecha, haz clic en el <b>Botón + Rojo</b>.</p>
        <p>1.2 Selecciona el proveedor en <b>Pagar a</b>.</p>
        <p>1.3 Indica la <b>Fecha</b> de registro y la <b>Fecha de vencimiento</b> (fecha de pago).</p>
        <p>1.4 En <b>Concepto</b>, busca un gasto existente o créalo con el acceso rápido de gasto.</p>
        <p>1.5 Digita el <b>Valor</b> del concepto y guárdalo.</p>
        <p>1.6 Opcional: agrega <b>Observaciones</b>.</p>
        <p>1.7 En la sección de pagos puedes registrar un abono parcial o el pago total.</p>
        <p>*El presupuesto queda ubicado en el calendario según su <b>fecha de vencimiento</b>.</p>
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
        <p>4.2 Modifica proveedor, fechas, concepto, valor u observaciones.</p>
        <p>4.3 Los cambios de encabezado y concepto se guardan al actualizar cada campo o al guardar el concepto.</p>
        <p>4.4 Si el presupuesto es origen de una serie recurrente, al guardar la pestaña <b>Recurrente</b> se recalculan los documentos generados (ver sección 6).</p>
</details>

<details><summary class="text-primary">5. Configurar un Presupuesto Recurrente</summary>
        <p>5.1 Abre el presupuesto origen (no uno generado automáticamente).</p>
        <p>5.2 Ve a la pestaña <b>Recurrente</b>.</p>
        <p>5.3 Activa <b>¿Es recurrente?</b>.</p>
        <p>5.4 Selecciona la <b>Frecuencia</b> (semanal, mensual, etc.).</p>
        <p>5.5 Indica la <b>Fecha de repetición</b>: fecha de pago / vencimiento de la primera repetición.</p>
        <p>5.6 Opcional: activa <b>¿Limitar repeticiones?</b> e ingresa la cantidad (ej. 12).</p>
        <p>5.7 Opcional: activa <b>¿Tiene fecha de finalización?</b> e indica hasta cuándo se genera la serie.</p>
        <p>5.8 Haz clic en <b>Guardar</b>.</p>
        <p>*Con cantidad o fecha fin, se generan los presupuestos de la serie en el calendario.</p>
        <p>*Sin límites, el origen debe quedar con saldo en cero; se genera la siguiente ocurrencia según la frecuencia.</p>
        <p>*El presupuesto origen conserva su fecha de registro; las fechas de la serie se reflejan en el <b>vencimiento</b> (fecha de pago).</p>
</details>

<details><summary class="text-primary">6. Actualizar o recalcular una serie recurrente</summary>
        <p>6.1 Abre el presupuesto <b>origen</b> de la serie (no un documento generado).</p>
        <p>6.2 En la pestaña <b>Recurrente</b>, modifica frecuencia, fechas, cantidad o fecha de finalización.</p>
        <p>6.3 Haz clic en <b>Guardar</b>.</p>
        <p>6.4 El sistema recalcula la serie:</p>
        <p>• Actualiza fechas, montos y conceptos de los documentos generados sin pagos.</p>
        <p>• Crea documentos faltantes si aumentan las repeticiones.</p>
        <p>• Anula los excedentes si disminuyen las repeticiones.</p>
        <p>6.5 Si algún documento generado ya tiene pagos, no se puede recalcular hasta anular o eliminar esos pagos.</p>
        <p>6.6 Para desactivar la recurrencia, apaga <b>¿Es recurrente?</b> y guarda: se anulan los documentos generados sin pagos.</p>
        <p>*Los documentos generados muestran un aviso y la configuración en solo lectura; edita siempre desde el origen.</p>
</details>

<details><summary class="text-primary">7. Registrar pagos o abonos</summary>
        <p>7.1 Abre el presupuesto.</p>
        <p>7.2 En la sección de pagos, registra el abono o el pago total (forma de pago y subcuenta según tu caja).</p>
        <p>7.3 El estado pasa a <b>Parcial</b> o <b>Pagado</b> según el saldo.</p>
        <p>7.4 En el calendario verás el color actualizado del evento.</p>
</details>

<details><summary class="text-primary">8. Crear un gasto rápido</summary>
        <p>8.1 Al crear o editar un presupuesto, si el concepto no existe, usa la opción de <b>gasto rápido</b>.</p>
        <p>8.2 Digita el <b>Nombre</b> y el <b>Valor</b> del gasto.</p>
        <p>8.3 Confirma: el gasto queda disponible como concepto y se carga en el presupuesto.</p>
</details>

<details><summary class="text-primary">9. Buscar un Presupuesto</summary>
        <p>9.1 Haz clic en el icono <b>Buscar</b> (Accesos Directos).</p>
        <p>9.2 Filtra por <b>Tercero</b> (proveedor) y/o <b>Concepto</b>.</p>
        <p>9.3 Visualiza el resultado en la vista Lista.</p>
        <p>9.4 Usa <b>Limpiar</b> para quitar los filtros.</p>
</details>
