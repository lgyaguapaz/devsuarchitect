# devsuarchitect
# Sistema de Banca Personas para la Financiera BP  
**Arquitectura escalable y segura para servicios financieros digitales**  


## 📌 Descripción  
Repositorio oficial del sistema de banca en línea para la Financiera BP, desarrollado bajo estándares de seguridad financiera y normativa ecuatoriana. Incluye:  
- Aplicación web (SPA) y móvil con autenticación biométrica.  
- Integración con sistemas Core bancarios y proveedores de notificaciones SMS y Correo Electrónico.  
- Arquitectura resiliente en AWS con alta disponibilidad.  

## 🚀 Características Principales  
- **Autenticación Biométrica**: Onboarding facia.  
- **Transferencias Interbancarias**: ISO 22002 usado por Banred.  
- **Notificaciones en Tiempo Real**: Multi-canal (SMS/Email) por cumplimiento normativo.  
- **Auditoría Trazable**: Event Sourcing con EventStoreDB.  

## 🛠 Stack Tecnológico  
| Capa               | Tecnologías                                                                 |  
|--------------------|-----------------------------------------------------------------------------|  
| **Frontend**       | Angular, Ionic+React/ Flutter                                               |  
| **Backend**        | .NET 8                                                                      |  
| **Bases de Datos** | Core Database (FitBank, Financia, Cobis), Redis, EventStoreDB               |  
| **Seguridad**      | Auth0 (OAuth2.0), AWS KMS, HashiCorp Vault                                  |  
| **Infraestructura**| AWS EC2,Amazon API Gateway                                                  |  


