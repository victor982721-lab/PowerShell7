# PowerShell7

Repositorio personal **PowerShell7**: evolución del proyecto PowerShell5 (RED).  
Si en PS5 el enfoque era **evitar errores comunes** (RED), en PS7 el enfoque es lo opuesto:  
**aplicar siempre los Scripts Fundamentales** como patrones canónicos.

---

## 🎯 Objetivo

Definir y consolidar un **catálogo de scripts fundamentales** que sirvan como base obligatoria para cualquier desarrollo en PowerShell 7.  
Cada script nuevo debe construirse aplicando **todos los Scripts Fundamentales aplicables**, asegurando:

- Seguridad (errores controlados, validación de parámetros, uso de SecretManagement).
- Consistencia (logging uniforme, métricas por fases, progreso estándar).
- Reutilización (mismo patrón para IO, red, compresión, cancelación).
- Calidad (tests con Pester, análisis con PSScriptAnalyzer).

---

## 📦 Instalación

> En desarrollo: futura publicación en PSGallery.  

Por ahora:  

```powershell
git clone https://github.com/victor982721-lab/PowerShell7.git
cd PowerShell7/src
Import-Module ./ScriptsFundamentales -Force
