# Multi-Cloud Red Team Analyst (MCRTA)

## Introducción

El programa **Multi-Cloud Red Team Analyst (MCRTA)** está diseñado para introducir a los estudiantes en el mundo del Red Team en entornos cloud modernos. A diferencia de cursos tradicionales centrados en una sola plataforma, MCRTA aborda simultáneamente los tres pilares del mercado actual:

- **Amazon Web Services (AWS)**
    
- **Microsoft Azure**
    
- **Google Cloud Platform (GCP)**
    

Las empresas reales operan en configuraciones híbridas y multi-cloud, así que las superficies de ataque ya no viven en un único proveedor. El objetivo del curso es entrenarte para detectar, explotar y encadenar errores de configuración distribuidos en múltiples nubes, siguiendo metodologías de Red Team seguras, repetibles y OPSEC-friendly.

Este curso es **100% práctico**, orientado a perfiles iniciales que buscan entrar al mundo del Cloud Red Teaming pero con resultados aplicables en entornos profesionales.

Al finalizar la formación podrás:

- Ejecutar operaciones de Red Team en un **entorno multi-cloud simulado**, con escenarios realistas de empresas híbridas.
    
- **Configurar credenciales y autenticación** para AWS CLI, Azure CLI y Google Cloud SDK.
    
- **Enumerar recursos críticos** en cada nube: identidades, redes, almacenamiento, compute, funciones serverless y configuraciones IAM.
    
- Identificar y explotar **misconfigurations comunes**: roles mal asignados, buckets expuestos, credenciales sobrantes, políticas demasiado permisivas, endpoints abiertos, etc.
    
- Encadenar vulnerabilidades entre nubes para lograr:
    
    - Movimiento lateral
        
    - Privilege escalation
        
    - Persistencia
        
    - Exfiltración o takeover de recursos críticos
        
- Capturar flags y cumplir los desafíos requeridos para obtener la **certificación MCRTA**.
    

---
## Estructura del curso MCRTA (versión profesional)

### Módulo 1 – Fundamentos de Multi-Cloud Red Teaming

- Concepto de arquitectura multi-cloud
    
- Modelo de responsabilidad compartida (los tres proveedores)
    
- Superficies de ataque comunes
    
- IAM universal: roles, permisos y políticas
    
- Herramientas del curso: AWS CLI, Azure CLI, gcloud, jq, herramientas Red Team
    
- Laboratorio base: preparación del entorno
    

### Módulo 2 – Enumeración Inicial y Configuración de Credenciales

- Configurar AWS CLI
    
- Configurar Azure CLI
    
- Configurar Google Cloud SDK
    
- Enumeración de identidades en las tres nubes
    
- Extracción de metadata desde máquinas virtuales
    
- Enumeración de almacenamiento: S3, Blob Storage, GCS
    
- Hands-on: Identificar y mapear un entorno híbrido
    

### Módulo 3 – AWS Red Team Essentials

- Enumeración profunda con CLI
    
- IAM privilege escalation paths
    
- Exploits comunes (S3 world-readable, Lambda abuse, SSRF to metadata)
    
- Escenarios encadenados
    
- Laboratorio CTF de AWS
    

### Módulo 4 – Azure Red Team Essentials

- Enumeración de Azure AD y RBAC
    
- Abuso de roles y service principals
    
- Exploits comunes (Blob Storage público, misconfiguraciones en App Services, Managed Identities expuestas)
    
- Movimiento lateral dentro de Azure
    
- Laboratorio CTF de Azure
    

### Módulo 5 – GCP Red Team Essentials

- Enumeración vía gcloud
    
- Abuso de Service Accounts
    
- Exploits comunes (permiso storage.objectViewer mal asignado, Cloud Functions, IAM wildcard)
    
- Movimiento lateral y privilege escalation
    
- Laboratorio CTF de GCP
    

### Módulo 6 – Multi-Cloud Attack Chains

- Identificar puntos débiles entre diferentes nubes
    
- Casos reales: credenciales filtradas, federación mal configurada, buckets expuestos
    
- Pivoting entre nubes: S3 → Blob → GCS
    
- Exfiltración de datos multi-cloud
    
- Escenario completo: ataque encadenado
    

### Módulo 7 – OPSEC, Persistencia y Reporte

- Mantener bajo perfil en entornos cloud
    
- Persistencia stealthy en AWS, Azure y GCP
    
- Minimizar logs y señales de actividad
    
- Crear informes profesionales estilo Red Team
    
- Preparación final para el CTF del examen MCRTA
    

