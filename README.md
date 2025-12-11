# 🚀 Laboratorios Microsoft 365 & Entra ID

Este repositorio documenta mis prácticas técnicas en Microsoft Learn y entornos de laboratorio, enfocadas en **IT Support y Seguridad básica**.  
Cada laboratorio incluye objetivos, pasos realizados, evidencias y aprendizajes clave.

---

## 1️⃣ Lab Zero Trust básico

### 🎯 Objetivo
Aplicar principios de Zero Trust en Entra ID.

### 🛠️ Pasos
- Configuración de **MFA obligatorio**.
- Creación de política de **Conditional Access**.
- Prueba de acceso desde **dispositivo no confiable**.

### 📸 Evidencias
<img width="1016" height="526" alt="usuario creado" src="https://github.com/user-attachments/assets/58c33a96-a109-4ec1-a170-bffe54fb13e7" />
<img width="413" height="382" alt="requiere MA" src="https://github.com/user-attachments/assets/57325f52-7aca-4b16-a947-70c218136fb9" />
<img width="401" height="485" alt="requiere install MA" src="https://github.com/user-attachments/assets/7a73e4ef-66d2-49de-8414-cc866c2f1226" />
<img width="385" height="448" alt="image" src="https://github.com/user-attachments/assets/6410c104-bed6-4e66-8e69-e52349ad264d" />
<img width="1286" height="577" alt="image" src="https://github.com/user-attachments/assets/c7d475d3-976b-467f-b764-1546a5bbaa7a" />
### Evidencia: Mensaje de bienvenida Copilot
Al iniciar sesión con el usuario de prueba en portal.office.com, aparece el mensaje:

> "New to Microsoft 365 Copilot. This is your Microsoft 365 Copilot home page—where you can see and access all of your Microsoft 365 apps..."

📌 Interpretación:
- El usuario tiene licencia asignada recientemente.
- El portal puede tardar en mostrar las apps.
- Se recomienda esperar 10 minutos y refrescar.


### 📚 Aprendizajes
- Importancia de MFA en Zero Trust.
- Cómo Conditional Access protege accesos.
- Diferencia entre dispositivos confiables y no confiables.



## 2️⃣ Administración básica (Entra ID / M365)

🎯 **Objetivo:** Gestionar usuarios y roles.  
🛠️ **Pasos:**  
- Crear grupos y asignar usuarios.  
- Revisar roles y permisos.  
- Resetear contraseñas.  

📸 **Evidencias:
<img width="706" height="553" alt="image" src="https://github.com/user-attachments/assets/a0eaceab-4a08-44b5-8ac4-efff0e2224c6" />
<img width="948" height="554" alt="image" src="https://github.com/user-attachments/assets/a5b3151c-20b5-4f28-9a99-63eabff9a811" />
<img width="288" height="184" alt="image" src="https://github.com/user-attachments/assets/a278d5f5-cee4-4378-9e8e-beb629d9a78b" />
<img width="286" height="256" alt="image" src="https://github.com/user-attachments/assets/6a3cd6d5-6293-48e6-9a00-176ead17f05a" />
<img width="469" height="577" alt="image" src="https://github.com/user-attachments/assets/4ebbccb2-36b3-47d5-8264-b6b945bfd892" />


📚 **Aprendizajes:** Diferencia entre roles y grupos, ciclo de vida de usuarios.

---

## 3️⃣ Colaboración y soporte (Microsoft 365)

🎯 **Objetivo:** Usar apps de productividad y simular soporte.  
🛠️ **Pasos:**  
- Acceder a Teams, Outlook y OneDrive.  
- Simular problemas comunes (login, compartir archivos).  
- Documentar resolución en un “artículo de conocimiento”.  

📸 **Evidencias:
<img width="592" height="547" alt="image" src="https://github.com/user-attachments/assets/08c8bc8a-2e78-44f5-8c53-d5670b13f0e2" />
<img width="570" height="523" alt="image" src="https://github.com/user-attachments/assets/a7f69541-20c6-40da-9d32-3ef56659758b" />
<img width="1366" height="768" alt="image" src="https://github.com/user-attachments/assets/a870a257-a0d5-46f6-97e2-120e95703606" />
<img width="1039" height="273" alt="image" src="https://github.com/user-attachments/assets/c72dff54-2fe1-4d45-8de4-690287cdb22c" />


- En Teams gratuito no aparece la opción de “crear equipo”.
- Usé la función **Comunidades** para simular un equipo de colaboración.
- Creé la comunidad `Lab-Soporte`, invité usuarios y compartí mensajes/archivos.

Ejemplo 1 – OneDrive
Problema simulado:
“No puedo abrir un archivo compartido en OneDrive.”
Resolución documentada:
Verificar conexión a internet.
Revisar permisos del archivo (¿tiene acceso el usuario?).
Probar abrir desde otro navegador.
Si persiste, cerrar sesión y volver a iniciar.

Ejemplo 2 – Teams
Problema simulado:
“No me llegan las notificaciones en Teams.”
Resolución documentada:
Revisar configuración de notificaciones en Teams.
Verificar que la app esté actualizada.
Probar en versión web para descartar problema local.

Ejemplo 3 – Outlook
Problema simulado:
“No puedo enviar correos desde Outlook.”
Resolución documentada:
Revisar conexión a internet.
Confirmar que la cuenta esté activa.
Probar enviar un correo de prueba a sí mismo.
Si falla, limpiar caché del navegador o app.

📚 **Aprendizajes:** Soporte básico de apps, importancia de KBs.

---

## 4️⃣ Automatización (PowerShell)

🎯 **Objetivo:** Automatizar tareas simples.  
🛠️ **Ejemplo de script:**
``powershell
## Crear usuario local de prueba
net user LabUser P@ssw0rd! /add


🌟 Conclusión
Estos laboratorios demuestran habilidades prácticas en:

Identidad y acceso (MFA, Conditional Access).

Administración de usuarios y roles.

Soporte de apps Microsoft 365.

Automatización con PowerShell.

Este portafolio sirve como evidencia para entrevistas en roles de Service Desk / IT Support.

📖 Mini‑Glosario bilingüe (EN/ES)
Service Desk & Soporte
Incident (Incidente): Evento que interrumpe un servicio.

Request (Solicitud): Petición de acceso o servicio nuevo.

SLA (Service Level Agreement / Acuerdo de nivel de servicio): Tiempo máximo para resolver.

Knowledge Base (Base de conocimiento): Artículos con soluciones comunes.

Identity & Access
MFA (Multi‑Factor Authentication / Autenticación multifactor): Verificación con más de un método.

Conditional Access (Acceso condicional): Políticas que controlan acceso según condiciones.

RBAC (Role‑Based Access Control / Control de acceso basado en roles): Permisos según rol.

Least Privilege (Principio de mínimo privilegio): Dar solo los permisos necesarios.

Endpoint Management
Endpoint (Dispositivo final): PC, laptop, móvil o VM.

Intune / Endpoint Manager: Herramienta para gestionar dispositivos y apps.

Patch Management (Gestión de parches): Actualización de seguridad y software.

Encryption (Cifrado): Protección de datos con BitLocker/FileVault.

Collaboration
Teams: Comunicación y reuniones.

SharePoint: Gestión de documentos y sitios.

OneDrive: Almacenamiento personal en la nube.

Outlook: Correo y calendario.

Security & Compliance
Defender: Protección contra malware y amenazas.

Sentinel: SIEM para monitoreo y respuesta de seguridad.

GDPR (Reglamento General de Protección de Datos): Normativa europea de privacidad.

ISO Compliance (Cumplimiento ISO): Estándares internacionales de seguridad y procesos.

Automation
PowerShell: Lenguaje de scripting para Windows y M365.

Script: Conjunto de comandos automatizados.

Template (Plantilla): Configuración estándar reutilizable.

CSI (Continuous Service Improvement / Mejora continua): Optimización de procesos.

# 📖 Knowledge Base Article – Resetear contraseña en Outlook

## 🎯 Objetivo
Guiar al usuario en el proceso de restablecer su contraseña de Outlook/Microsoft 365 cuando no puede iniciar sesión.

---

## 🛠️ Pasos

1. Ir a la página de inicio de sesión de Outlook: [https://outlook.office.com](https://outlook.office.com).
2. Ingresar el correo electrónico de la cuenta.
3. Seleccionar **Forgot my password** (Olvidé mi contraseña).
4. Elegir el método de verificación (SMS, correo alternativo o Microsoft Authenticator).
5. Ingresar el código recibido.
6. Crear una nueva contraseña segura (mínimo 8 caracteres, incluir mayúsculas, minúsculas, números y símbolos).
7. Confirmar y volver a iniciar sesión.

---

## 📸 Evidencias
*(Agregar capturas de pantalla del flujo de recuperación, sin mostrar datos sensibles).*

---

## 📚 Notas
- La contraseña debe ser diferente a las últimas usadas.  
- Si el usuario no tiene métodos de recuperación configurados, debe contactar al administrador de TI.  
- Tiempo estimado de resolución: **5 minutos**.  

---

## ✅ Conclusión
Este procedimiento permite al usuario recuperar acceso a su cuenta de Outlook/M365 de forma segura y rápida, cumpliendo con las políticas de seguridad de la organización.


# 📖 Knowledge Base Article – Instalar Microsoft Teams en Windows

## 🎯 Objetivo
Guiar al usuario en la instalación de Microsoft Teams en un equipo con Windows 10/11.

---

## 🛠️ Pasos

1. Abrir el navegador y acceder a la página oficial: [https://www.microsoft.com/es-co/microsoft-teams/download-app](https://www.microsoft.com/es-co/microsoft-teams/download-app).
2. Hacer clic en **Descargar para escritorio**.
3. Guardar el archivo de instalación en la carpeta de Descargas.
4. Ejecutar el archivo descargado (`Teams_windows_x64.exe`).
5. Seguir el asistente de instalación hasta finalizar.
6. Una vez instalado, abrir Teams desde el menú Inicio.
7. Iniciar sesión con la cuenta corporativa o personal de Microsoft.

---

## 📸 Evidencias
*(Agregar capturas de pantalla del proceso de descarga, instalación y primer inicio de sesión).*

---

## 📚 Notas
- Requiere Windows 10 o superior.  
- Si el usuario ya tiene Teams preinstalado, verificar actualizaciones desde la aplicación.  
- Tiempo estimado de resolución: **10 minutos**.  

---

## ✅ Conclusión
Este procedimiento permite instalar Microsoft Teams en Windows de forma rápida y segura, asegurando que el usuario pueda acceder a reuniones y colaboración en línea.
