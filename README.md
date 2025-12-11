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
<img width="401" height="485" alt="requiere install MA" src="https://github.com/user-attachments/assets/7a73e4ef-66d2-49de-8414-cc866c2f1226" />

<img width="385" height="448" alt="image" src="https://github.com/user-attachments/assets/6410c104-bed6-4e66-8e69-e52349ad264d" />


### 📚 Aprendizajes
- Importancia de MFA en Zero Trust.
- Cómo Conditional Access protege accesos.
- Diferencia entre dispositivos confiables y no confiables.

---

## 2️⃣ Lab Entra ID Admin

### 🎯 Objetivo
Practicar administración básica de identidades en Entra ID.

### 🛠️ Pasos
- Asignación de **roles**.
- Creación y gestión de **usuarios**.
- Organización en **grupos**.
- Configuración de **policies simples**.

### 📸 Evidencias
*(Agregar capturas aquí)*

### 📚 Aprendizajes
- Roles vs permisos.
- Buenas prácticas de grupos.
- Policies para control básico.

---

## 3️⃣ Lab Microsoft 365 Admin Center

### 🎯 Objetivo
Gestionar usuarios y licencias desde el Admin Center.

### 🛠️ Pasos
- Administración de **licencias**.
- Creación y gestión de **usuarios**.
- **Password reset**.
- Revisión de **logs básicos**.

### 📸 Evidencias
*(Agregar capturas aquí)*

### 📚 Aprendizajes
- Relación entre licencias y servicios.
- Flujo de soporte para usuarios.
- Logs como herramienta de diagnóstico.

---

## 4️⃣ Lab Intune – configuración mínima

### 🎯 Objetivo
Configurar Intune para gestión básica de dispositivos.

### 🛠️ Pasos
- **Enrolar dispositivo**.
- Crear **política de cumplimiento**.
- **App deployment básico**.

### 📸 Evidencias
*(Agregar capturas aquí)*

### 📚 Aprendizajes
- Diferencia entre enrolamiento y compliance.
- Cómo distribuir apps en Intune.
- Seguridad mínima en dispositivos.

---

## 5️⃣ Mini-script PowerShell

### 🎯 Objetivo
Automatizar tareas básicas con PowerShell.

### 🛠️ Ejemplo
```powershell
# Crear usuario de prueba en Entra ID
New-AzureADUser -DisplayName "Lab User" -UserPrincipalName "labuser@tenant.onmicrosoft.com" -AccountEnabled $true -PasswordProfile @{Password="P@ssw0rd!"}
