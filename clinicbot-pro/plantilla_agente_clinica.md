# 🏥 Plantilla Agente IA para Clínicas — Nuika AI

---

## 📦 NOMBRE DEL PRODUCTO
**"ClinicBot Pro" — Tu recepcionista IA que nunca descansa**

---

## 💡 FUNCIONES DEL AGENTE

1. **Responde preguntas frecuentes 24/7**
   - Horarios, ubicación, especialidades, precios de consulta, seguros aceptados
   - Preparación para citas (en ayunas, qué llevar, etc.)

2. **Capta y cualifica leads**
   - Recoge nombre, teléfono, tipo de consulta y urgencia
   - Los guarda automáticamente en un CRM simple

3. **Gestiona citas por WhatsApp**
   - Propone horarios disponibles
   - Confirma, recuerda y permite cancelar citas

4. **Seguimiento post-consulta**
   - Envía recordatorio de próxima revisión
   - Pide valoración/reseña al paciente tras la visita

5. **Desvío inteligente**
   - Si detecta urgencia real, redirige al teléfono de guardia
   - Si el paciente quiere hablar con una persona, transfiere la conversación

---

## 💰 PRECIO DE VENTA RECOMENDADO

| Plan | Precio | Incluye |
|------|--------|---------|
| **Starter** | 497€ pago único | Instalación + 3 meses soporte básico |
| **Pro Mensual** | 197€/mes | Instalación + mantenimiento + mejoras continuas |
| **Enterprise** | Desde 997€ | Multicanal (WhatsApp + Web + Email) + CRM avanzado |

**Margen estimado:** Montas el agente en 3–5 horas. Coste real tuyo: tu tiempo.

---

## 🌐 LANDING PAGE — ESTRUCTURA

### HERO
**Título:** "Tu clínica atendiendo pacientes a las 3 de la mañana. Sin contratar a nadie."
**Subtítulo:** "ClinicBot Pro responde, agenda y capta pacientes nuevos mientras tú duermes o trabajas."
**CTA:** [Quiero ver una demo gratis →]

### BLOQUE PROBLEMA
- ¿Pierdes pacientes porque no respondes fuera de horario?
- ¿Tu recepcionista está saturada con llamadas repetitivas?
- ¿Los recordatorios de cita los haces manualmente?

### BLOQUE SOLUCIÓN
ClinicBot Pro hace todo eso automáticamente. Es un agente IA conectado a tu WhatsApp que trabaja 24/7, sin errores y sin coste de nómina.

### LO QUE INCLUYE
✅ Respuestas automáticas personalizadas para tu clínica
✅ Captación de nuevos pacientes con formulario inteligente
✅ Recordatorios de cita por WhatsApp
✅ Panel de control para ver todos los leads
✅ Instalación y configuración completa

### PRUEBA SOCIAL (placeholder)
"Desde que tenemos ClinicBot Pro, hemos reducido las llamadas a recepción un 60% y captamos 8–12 nuevos pacientes al mes desde WhatsApp." — Dr. [Nombre], Clínica [X]

### FAQ
- ¿Funciona con mi WhatsApp actual? Sí.
- ¿Necesito conocimientos técnicos? No, lo configuramos nosotros.
- ¿Qué pasa si el paciente quiere hablar con una persona? El agente lo transfiere.

### CTA FINAL
**[Agenda una demo de 20 minutos — es gratis]**

---

## ✉️ MENSAJE DE VENTA (WhatsApp / Email)

**Asunto / Apertura:**
"¿Tu clínica pierde pacientes fuera de horario?"

---

Hola [Nombre],

Te escribo porque trabajo con clínicas como la tuya ayudándoles a no perder ni un paciente por falta de respuesta.

Hemos creado **ClinicBot Pro**: un agente IA que responde por WhatsApp 24/7, agenda citas automáticamente y capta los datos de cada nuevo paciente interesado.

Clínicas similares están captando 8–12 pacientes nuevos al mes solo desde WhatsApp, sin contratar más personal.

El setup completo son **497€** (una sola vez) y lo tienes funcionando en 48 horas.

¿Te hago una demo de 20 minutos esta semana para que lo veas en acción?

Un saludo,
[Tu nombre] — Nuika AI

---

## 🛠️ PASOS PARA MONTARLO EN BASE44

### PASO 1 — Crear la entidad de datos
- Entidad: `PacienteLead`
- Campos: `nombre`, `telefono`, `tipo_consulta`, `urgencia`, `fecha_contacto`, `estado` (nuevo/contactado/cita_agendada)

### PASO 2 — Configurar el agente IA
- En Base44 Superagent, definir la identidad del agente:
  - Nombre: ClinicBot (o el nombre de la clínica)
  - Instrucciones: responder FAQs de la clínica, captar datos del paciente, gestionar citas
- Subir al agente el documento con: horarios, servicios, precios, FAQs específicas de esa clínica

### PASO 3 — Conectar WhatsApp
- Vincular el canal de WhatsApp del cliente al agente
- Activar en modo `always` para que responda a todos los mensajes

### PASO 4 — Automatizaciones
- Automatización 1: cuando se crea un nuevo `PacienteLead` → enviar notificación al médico/recepcionista
- Automatización 2: 24h antes de la cita → enviar recordatorio al paciente
- Automatización 3: 24h después de la cita → enviar mensaje de seguimiento y pedir reseña

### PASO 5 — Panel de control
- Crear vista de entidad `PacienteLead` con filtros por estado
- El cliente ve en tiempo real todos los leads captados

### PASO 6 — Personalización por cliente
- Sustituir FAQs genéricas por las de la clínica específica
- Adaptar horarios, especialidades y nombre del agente
- Tiempo estimado: 2–3 horas por cliente nuevo

---

## 📊 ARGUMENTOS DE VENTA CLAVE

- **ROI claro:** Un solo paciente nuevo al mes ya paga el servicio
- **Sin riesgo técnico:** Nuika AI instala y mantiene todo
- **Sin cambios en su flujo actual:** Se integra en su WhatsApp existente
- **Diferenciador competitivo:** Pocas clínicas en España tienen esto aún

---

## 🎯 NICHOS PRIORITARIOS DENTRO DE CLÍNICAS

1. Clínicas dentales (alto ticket, muchas FAQs)
2. Clínicas de estética (consultas frecuentes, citas online)
3. Fisioterapia y rehabilitación (pacientes recurrentes)
4. Psicología y terapia (alta demanda, discreción importante)
5. Veterinarias (urgencias, recordatorios vacunas)

---

*Creado por Nuika AI — nuika.ai*
