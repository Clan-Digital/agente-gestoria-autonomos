# Datos del cliente · Agente Gestoría

Documento que lee el Agente Gestoría en cada pasada. Cómo trabaja el agente está en el Manual en Producción (solo lectura). Aquí va solo lo propio de este cliente. Si cambia algo, se cambia aquí.

## Quién

- {{NOMBRE_FISCAL}} · {{NOMBRE_COMERCIAL}} · NIF {{NIF}} · NIF-IVA {{NIF_IVA}}.
- Domicilio fiscal: {{MUNICIPIO_CP}} ({{COMUNIDAD}}). {{IRPF}}. {{ACTIVIDADES}}.
- A qué se dedica: {{A_QUE_SE_DEDICA}}.
- Fecha de alta como autónomo: {{FECHA_ALTA}}.
- Mapa fiscal: {{MODELOS}}.
- Banderas pendientes del alta: {{BANDERAS}}.

## Dónde está cada cosa

- Excel: {{EXCEL_NOMBRE}}, id {{EXCEL_ID}}.
- Carpeta del agente: {{CARPETA_AGENTE_ID}}.
- Carpetas de facturas del año {{ANIO}}:
  - 1T: Ingresos {{1T_INGRESOS_ID}}; Gastos {{1T_GASTOS_ID}}
  - 2T: Ingresos {{2T_INGRESOS_ID}}; Gastos {{2T_GASTOS_ID}}
  - 3T: Ingresos {{3T_INGRESOS_ID}}; Gastos {{3T_GASTOS_ID}}
  - 4T: Ingresos {{4T_INGRESOS_ID}}; Gastos {{4T_GASTOS_ID}}
- Organización de las facturas: {{ORGANIZACION_FACTURAS}} (propia del cliente / ordenada por el agente con su permiso / estructura nueva del agente).
- Sitio elegido para lo nuevo que cree el agente: {{SITIO_NUEVO}}.
- Facturas emitidas: {{ORIGEN_FACTURAS_EMITIDAS}}.
- Fecha de inicio: {{FECHA_INICIO}}. Lo anterior se revisa en la revisión inicial de 12 meses.

## Banco

- Bancos de la actividad: {{BANCOS}}.
- Conector de banco: {{CONECTOR_BANCO}} (si no hay, el cliente marca los cobros en el Excel).
- Cuentas excluidas: {{CUENTAS_EXCLUIDAS}}.
- Gastos personales: {{REGLA_GASTOS_PERSONALES}}.
- Traspasos propios: {{REGLA_TRASPASOS}}.
- Cuota de autónomos: se paga desde {{BANCO_CUOTA}}.
- Plataformas de cobro o pago: {{PLATAFORMAS}}.

## Correo y avisos

- Correo donde llegan las facturas de proveedores: {{EMAIL_FACTURAS}}.
- Etiqueta para los correos de facturas ya gestionados: «Gestionado por IA/Agente Gestoría».
- Avisos: método {{METODO_AVISOS}} (gmail / resend). Desde {{EMAIL_REMITENTE}} a {{EMAIL_AVISOS}}. Asunto «Agente Gestoría | {{NOMBRE_COMERCIAL}}: …». Con Gmail, el aviso lleva la etiqueta «Gestionado por IA/Agente Gestoría» y el cliente puede escribir al agente en ese alias.
- Hora de la pasada diaria: {{HORA_PASADA}} (hora de España).
- Registro de actividad (lo lee Clan Digital): {{REGISTRO}} (hoja {{REGISTRO_ID}} compartida en solo lectura con cmanashuete@gmail.com, o email diario a esa dirección).
- Respuestas válidas: solo las enviadas desde {{EMAIL_RESPUESTAS}}.
- Manual de marca para el Excel: {{MANUAL_MARCA}}.

## Reglas

- Las reglas contables de este cliente (las acordadas al instalar y las que dé por email) están en la pestaña «Reglas del cliente» del Excel. Aquí no se repiten.
