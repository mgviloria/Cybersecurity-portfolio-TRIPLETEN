# Proyecto 08: Simulador Cloud Identity Console - Investigación de IAM en la Nube

## 🎯 Objetivos del Proyecto
* Investigar anomalías de uso en servicios de nube (análisis de picos en `AssumeRole`).
* Auditar políticas JSON de IAM reales para identificar permisos efectivos y desviaciones de configuración.
* Trazar grafos de confianza entre cuentas de nube para detectar vectores de movimiento lateral.
* Realizar escaneo de secretos en repositorios de código para hallar la causa raíz de una filtración.
* Formular y contrastar hipótesis en paralelo contra la evidencia de logs en tiempo real.
* Ejecutar medidas de contención y diseñar políticas de privilegio mínimo probadas contra escenarios operativos.
* Documentar el incidente alineando las técnicas observadas con el marco MITRE ATT&CK.

## 🛠️ Herramientas y Conceptos
* Seguridad e Identidad en la Nube (AWS IAM, JSON Policies).
* Escaneo de Secretos y Hardening de Repositorios.
* Principio de Privilegio Mínimo (*Least Privilege*).
* Mapeo de Amenazas a MITRE ATT&CK.

## 📝 Resultados y Aprendizajes
Identificación precisa del vector de entrada en la infraestructura cloud mediante auditoría de IAM y repositorios, aplicando exitosamente políticas remediadas de privilegio mínimo sin afectar la operación.
