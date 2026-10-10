# EnfoqueBalanc

*Organiza tu tiempo. Equilibra tus finanzas.*

EnfoqueBalanc combina agenda y finanzas personales en una aplicación para Android y Windows. Está pensada para estudiantes, empleados y trabajadores independientes que quieren organizar sus compromisos, avanzar paso a paso y entender mejor su flujo de dinero.

**Estado:** validación local en curso. No hay instaladores ni sincronización pública disponibles.

## Qué ofrece

- Agenda separada en **Historial**, **Hoy** y **Planificación**, con tareas, actividades de jornada y notas vinculadas.
- Repetición semanal en los días elegidos hasta una fecha final; los cambios o eliminaciones pueden aplicarse a la fecha actual o a las actividades futuras de la serie.
- Calendario de día, semana y mes. El día usa una vista Gantt de 24 horas; hoy se desplaza a la hora actual y otras fechas se recorren manualmente.
- Finanzas personales en quetzales: ingresos, gastos, compromisos recurrentes, presupuestos, créditos y cuentas por cobrar.
- Registro de aportes y retiros de ahorro con un saldo informativo separado del dinero disponible para gastos.
- Cuatro temas visuales: claro, oscuro, azul claro y rosa.
- Acompañamiento en español con IA local: motivación, reflexión, división de actividades extensas en pasos pequeños y orientación financiera. La IA sugiere; no registra pagos ni mueve dinero.
- Historial local cifrado, disponible sin cuenta ni conexión a un servidor.

## IA en el dispositivo

La aplicación integra un modelo Qwen compacto que se ejecuta localmente mediante llama.cpp. Puede ayudar a dividir actividades de al menos una hora y generar orientación contextual según los datos disponibles. Las operaciones financieras y los estados de las tareas se controlan con reglas de la aplicación; un texto de IA nunca marca una tarea como realizada ni registra un movimiento.

## Guía y capturas

- [Guía de uso](../../docs/guia-enfoquebalanc.html)
- [Presentación detallada](../../docs/agenda-inteligente.html)
- Captura de primera apertura en Android: `../../docs/capturas/enfoquebalanc-inicio-android.png`

Las próximas capturas públicas se tomarán con información demostrativa, sin datos personales ni financieros reales.

## Tecnologías

Flutter · Dart · Android · Windows · llama.cpp · Qwen.

## Disponibilidad

La edición actual está diseñada para uso local gratuito. El inicio de sesión y la sincronización entre dispositivos no se ofrecen en esta etapa; una suscripción futura no está disponible para compra. Las descargas se anunciarán cuando existan paquetes firmados y pruebas de publicación aprobadas.

El código fuente completo, las pruebas, el modelo, la documentación técnica interna y la configuración de desarrollo permanecen privados. Este catálogo no contiene un proyecto compilable. Las dependencias y el modelo de terceros conservan sus licencias y avisos correspondientes.
