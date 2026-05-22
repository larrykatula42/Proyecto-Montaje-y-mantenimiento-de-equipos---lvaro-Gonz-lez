# Proyecto-Montaje-y-mantenimiento-de-equipos---lvaro-Gonz-lez
Módulo 0221 — Montaje y Mantenimiento de Equipos

Proyecto Intermodular · 1.º SMR · Curso 2025–2026

¿De qué trata este módulo?

Este módulo forma parte del Proyecto Intermodular del Ciclo Formativo de Grado Medio en Sistemas Microinformáticos y Redes (SMR). Corresponde al módulo Montaje y Mantenimiento de Equipos (código 0221) de 1.º curso.

El objetivo es diseñar y justificar la infraestructura de hardware de una pequeña empresa, seleccionando los componentes adecuados y explicando tanto el proceso de montaje como las tareas de mantenimiento necesarias.

Todo el trabajo está orientado a la empresa TechOficina S.L., utilizada también en el resto de módulos del Proyecto Intermodular.

La empresa: TechOficina S.L.
Campo	Datos
Nombre	TechOficina S.L.
Actividad	Soporte y mantenimiento informático para pequeñas empresas
Ubicación	Calle Mayor 14, 2.º A — 28013 Madrid
Empleados	6 personas (gerente, técnica senior, 2 técnicos junior, administrativo y becario)
Clientes	Pequeños negocios locales sin departamento TI propio

La empresa necesita:

Equipos de oficina para trabajo diario
Portátiles para desplazamientos
Un servidor para centralizar información
Equipamiento de red básico (router y switch)

El objetivo es implementar una solución eficiente, equilibrada y adecuada al tamaño de la empresa, evitando hardware innecesariamente costoso.

Documentos creados
1. 05_Montaje_y_Mantenimiento.docx — Documento principal

Documento Word con el desarrollo completo del módulo, organizado en siete secciones:

Sección	Contenido
1. Contexto de la empresa	Descripción general y justificación del proyecto
2. Análisis de necesidades	Relación de equipos necesarios y justificación
3. Configuración del equipo	Componentes seleccionados, precios y motivos de elección
4. Montaje paso a paso	Guía de montaje y recomendaciones de seguridad
5. Mantenimiento	Limpieza, control de temperatura, sustituciones y copias de seguridad
6. Inventario	Resumen de los equipos de la empresa
7. Conclusión	Valoración final y justificación del presupuesto
2. 06_Inventario_Tecnico_Hardware.xlsx — Inventario técnico

Libro de Excel compuesto por cinco hojas:

Hoja	Contenido
Inventario General	Tabla de todos los equipos con ID, tipo, modelo, usuario y especificaciones
Ficha PC Estándar	Configuración técnica completa del PC estándar
Ficha PC Reforzado	Configuración avanzada destinada a la técnica senior
Plan de Mantenimiento	Tareas periódicas de mantenimiento y responsables
Presupuesto	Coste total del hardware con cálculos automáticos
Hardware elegido — Resumen
PC estándar (3 unidades — PC-001, PC-003 y PC-004)
Componente	Modelo	Precio aproximado
CPU	Intel Core i5-12400 (6C/12T)	~150 €
Placa base	ASUS PRIME H610M-K D4 (µATX)	~80 €
RAM	16 GB DDR4 3200 MHz (2×8 GB)	~35 €
Almacenamiento	SSD NVMe 500 GB Kingston NV2	~40 €
Fuente	Be Quiet! System Power 10 400W 80+ Bronze	~45 €
Caja	Fractal Design Pop Mini (µATX)	~50 €
GPU	Integrada Intel UHD 730	0 €
Sistema operativo	Windows 11 Pro OEM	~100 €

Coste total aproximado: ~500 €

PC reforzado (1 unidad — PC-002)

Equipo destinado a la técnica senior.

Diferencias respecto al PC estándar:

Componente	Mejora
CPU	Intel Core i7-12700 (12 núcleos)
RAM	32 GB DDR4
SSD	1 TB NVMe
Motivo

Este equipo está preparado para:

Virtualización
Máquinas virtuales
Captura y análisis de tráfico de red
Herramientas técnicas avanzadas

Coste aproximado: ~650 €

Resto del hardware
Equipo	Modelo	Unidades
Portátil técnico	Lenovo ThinkPad E15 Gen 4	2
Servidor NAS	Synology DS923+	1
Impresora multifunción	HP LaserJet Pro M428dw	1
SAI / UPS	APC Back-UPS 600 VA	1
Switch gestionable	TP-Link TL-SG1016DE (16 puertos)	1
Router / Firewall	Mikrotik hEX S	1

Presupuesto total estimado: ~4.200 €
(Sin IVA y sin incluir Microsoft 365)

Justificación de las decisiones principales
¿Por qué Intel Core i5-12400 para los equipos estándar?

Es un procesador de gama media con buen rendimiento en:

Ofimática
Navegación web
Soporte remoto
Multitarea básica

Además, incorpora gráfica integrada Intel UHD 730, lo que evita la necesidad de una tarjeta gráfica dedicada y reduce el coste del equipo.

¿Por qué 16 GB de RAM?

El uso simultáneo de aplicaciones como:

Microsoft Teams
Navegadores con múltiples pestañas
Excel y Word

puede consumir fácilmente entre 8 y 10 GB de memoria. Con 16 GB se garantiza un funcionamiento fluido y margen para futuras necesidades.

¿Por qué SSD NVMe en lugar de disco duro?

Los SSD NVMe ofrecen velocidades muy superiores a las de un HDD tradicional.

Ventajas principales:

Arranque rápido de Windows
Apertura inmediata de programas
Mejor experiencia de uso
Mayor productividad diaria

El incremento de coste queda compensado por el rendimiento obtenido.

¿Por qué una fuente Be Quiet!?

Las fuentes de alimentación de baja calidad pueden provocar averías e inestabilidad.

La gama seleccionada ofrece:

Buena relación calidad/precio
Certificación 80+ Bronze
Mayor eficiencia energética
Componentes más fiables y duraderos
¿Por qué un equipo reforzado para la técnica senior?

La técnica senior utiliza herramientas con un consumo elevado de recursos:

VirtualBox
Hyper-V
Wireshark
Herramientas de análisis y diagnóstico

Por este motivo se justifica el uso de:

Más núcleos de CPU
Mayor cantidad de RAM
Más almacenamiento SSD
Guía de montaje — Resumen de los pasos
Preparar la caja e instalar separadores
Instalar el procesador en el socket LGA1700
Aplicar pasta térmica y montar el disipador
Instalar la memoria RAM en dual channel
Instalar el SSD NVMe M.2
Fijar la placa base a la caja
Instalar la fuente de alimentación
Conectar cableado interno
Realizar primera comprobación en BIOS
Instalar Windows 11 Pro desde USB
Recomendaciones de seguridad
Desconectar siempre la corriente antes de manipular componentes.
Descargar electricidad estática tocando una superficie metálica.
Manipular los componentes con cuidado para evitar daños físicos o eléctricos.

Autor:

Álvaro González
