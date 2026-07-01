## **PLANILLAR ZONA**

Sigue los pasos para agrupar los documentos pendientes de una zona y generar la planilla de distribución.

La sección **Documentos Pendientes por Planilla** muestra las **Facturas de Venta** y **Remisiones de Salida** que aún no tienen planilla asignada. Desde aquí validas la ruta del día y generas la planilla del recorrido.

<details><summary class="text-primary">1. Consultar documentos pendientes</summary>
        <p>1.1 Al ingresar verás el listado de documentos con <b>planilla en cero</b> (sin planilla asignada).</p>
        <p>1.2 Cada fila muestra: <b>ID</b>, <b>Fecha</b>, <b>Cliente</b>, <b>Establecimiento</b>, <b>Ruta/Asesor</b> y <b>Total Pedido</b>.</p>
        <p>1.3 Solo aparecen <b>Facturas de Venta</b> y <b>Remisiones de Salida</b> en estados contables <b>1 y 2</b> (vigentes para distribución).</p>
        <p>1.4 En el panel <b>Buscar</b> puedes filtrar por:</p>
        <p>• <b>Zona:</b> zona del cliente en su ficha.</p>
        <p>• <b>Desde ID:</b> documentos a partir de un número consecutivo.</p>
        <p>1.5 Selecciona un <b>Reporte</b> y haz clic en <b>Imprimir</b> para obtener listados de la sección.</p>
</details>

<details><summary class="text-primary">2. Generar una planilla</summary>
        <p>2.1 Haz clic en <b>Planillar Zona...</b> (botón inferior derecho). El botón solo aparece si hay documentos pendientes en el listado.</p>
        <p>2.2 Selecciona la <b>Zona</b>. El sistema valida que existan pedidos pendientes <b>abonados a esa zona</b> y muestra:</p>
        <p>• <b>No. Pedidos:</b> cantidad de documentos de venta a incluir.</p>
        <p>• <b>Total Ruta:</b> valor total de esos documentos.</p>
        <p>2.3 Selecciona el <b>Día Entrega</b>. Debes elegir la zona primero. El sistema compara los pedidos con la ruta del día y muestra:</p>
        <p>• <b>Clientes en Ruta:</b> pedidos con orden de visita para ese día.</p>
        <p>• <b>Clientes Fuera de Ruta:</b> pedidos de la zona que no están en la ruta del día seleccionado.</p>
        <p>2.4 Haz clic en <b>Generar Planilla</b>.</p>
        <p>2.5 Aparece la confirmación con el número de planilla. Puedes ir a <b>Planillas</b> para consultar, imprimir reportes o liquidar.</p>
</details>

<details><summary class="text-primary">3. ¿Qué hace el sistema al generar?</summary>
        <p>Al confirmar, el sistema automáticamente:</p>
        <p>• Vincula las <b>Facturas y Remisiones</b> pendientes de la zona seleccionada.</p>
        <p>• Vincula el <b>Cargue de Zonas</b> pendiente de esa ruta (inventario inicial).</p>
        <p>• Calcula los totales de <b>pedidos</b> (líneas tipo P) y <b>cambios</b> (líneas tipo C).</p>
        <p>• Asigna el <b>orden de visita</b> según la ruta configurada para el día de entrega.</p>
        <p>• Crea el <b>Descargue de Zonas</b> con el inventario teórico no vendido (cargue − ventas), cuando aplica.</p>
</details>

<details><summary class="text-primary">4. Requisitos previos</summary>
        <p>Antes de planillar verifica que:</p>
        <p>• Los pedidos estén registrados como Factura o Remisión y tengan la <b>zona correcta en el abonado</b> del documento.</p>
        <p>• Exista un <b>Cargue de Zonas</b> para la ruta, si manejas inventario en distribución.</p>
        <p>• La <b>ruta de visita</b> esté configurada en <b>Distribución → Rutas</b>, con el día de entrega y el orden de los clientes.</p>
        <p>• Los documentos no estén anulados ni contabilizados (estado contable 3).</p>
</details>

<details><summary class="text-primary">5. Mensajes frecuentes</summary>
        <p><b>"No se encuentran documentos para esta zona"</b> — No hay facturas ni remisiones pendientes abonadas a la zona seleccionada.</p>
        <p><b>"Debe seleccionar una zona antes de generar una planilla"</b> — Elija la zona en el formulario.</p>
        <p><b>"Debe seleccionar un día de entrega antes de generar una planilla"</b> — Elija el día de entrega en el formulario.</p>
        <p><b>"Debe seleccionar una zona antes de seleccionar un día de entrega"</b> — Primero zona, luego día.</p>
        <p><b>"No se encontraron documentos para actualizar"</b> — Al generar no hubo documentos válidos para vincular; revise zona, estados contables y tipos de documento.</p>
</details>
