DASHBOARD DE EXPEDIENTES PENDIENTES - AAA CAÑETE FORTALEZA

Abre index.html en Visual Studio Code y utiliza Live Server para ver el dashboard.
La información se carga desde el Google Sheets configurado en index.html.

CLASIFICACIÓN SAP
La hoja SAP es el catálogo completo. Su columna A debe tener el encabezado
PROCEDIMIENTO y, debajo, un procedimiento SAP por fila. La columna B con el
texto SAP puede mantenerse, pero la clasificación usa únicamente la columna A.

Un expediente se marca SAP cuando su PROCEDIMIENTO coincide con una fila de
la columna A de SAP. Se ignoran el número inicial, tildes, signos y espacios;
no se usan coincidencias parciales ni el CUT ni la columna SAP de pendientes.

PARA AÑADIR OTRO PROCEDIMIENTO SAP
1. Abre el Google Sheets conectado al dashboard y entra a la pestaña SAP.
2. Añade el procedimiento en la siguiente fila libre de la columna A.
3. Guarda el cambio y recarga el dashboard en el navegador.
No es necesario editar el HTML. Si sustituyes el Google Sheets completo,
actualiza la constante SHEET_ID al comienzo del bloque <script> de index.html.
