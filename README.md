# EduMentor - Tu Asistente de Estudio Inteligente
### Proyecto Parcial 3 - UFG
**Autor:** Brayan Rafael Mina Rodriguez
**Carnet:** MR100518

## 1. Descripcion del Proyecto
EduMentor es una app movil desarrollada con la plataforma Glide (No-Code) que ayuda a estudiantes universitarios a mejorar sus habitos de estudio. La app analiza las horas de estudio y los temas registrados para ofrecer recomendaciones inteligentes mediante un sistema de IA simulada (reglas) o IA real via API (Make + OpenAI).

## 2. Objetivo Principal
Facilitar la organizacion academica del estudiante mediante recordatorios, registro de progreso y sugerencias adaptadas a su ritmo de aprendizaje.

## 3. Plataforma No-Code Utilizada
Glide con autenticacion OTP, Google Sheets y compatibilidad con Make/Zapier.

## 4. Funcionalidades
- Login OTP (correo)
- Perfil del estudiante (carrera, objetivos)
- Registro diario de horas y materias
- Asistente Inteligente (IA simulada o real)
- Panel de progreso
- Integracion opcional con OpenAI via Make/Zapier

## 5. Arquitectura e Infraestructura
Ver docs/Diagrama_Infraestructura_EduMentor.png y .drawio

Descripcion:
El usuario accede desde su telefono a la app Glide, la cual conecta con Google Sheets y, opcionalmente, con Make/Zapier que ejecuta un prompt de IA y devuelve una respuesta como recomendacion.

Usuario -> Glide App -> (Sheets y Make -> OpenAI)

## 6. Costos y Rentabilidad
CAPEX: 0 USD (recursos existentes)
OPEX mensual estimado: 50 USD (Glide + dominio + conexion IA)
Punto de equilibrio: 50 usuarios activos a 1 USD mensual.

## 7. Enlaces
- Prototipo Glide: [pendiente]
- Video MVP (YouTube): [pendiente]
- Video PROMPT (YouTube): [pendiente]

## 8. Como probar
1. Abrir el enlace publico del prototipo
2. Iniciar sesion con correo (OTP)
3. Registrar horas de estudio y materias
4. Revisar recomendaciones y panel de progreso

## 9. Licencia
Proyecto academico para la Universidad Francisco Gavidia, sin fines comerciales.
