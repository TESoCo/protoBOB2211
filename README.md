# 🏗️ BOB - Building Optimization Baseline

<div align="center">

**Sistema Integral de Gestión de Proyectos de Construcción**

[![Java](https://img.shields.io/badge/Java-17-orange.svg)](https://www.oracle.com/java/)
[![Spring Boot](https://img.shields.io/badge/Spring%20Boot-3.x-brightgreen.svg)](https://spring.io/projects/spring-boot)
[![MySQL](https://img.shields.io/badge/MySQL-8.0-blue.svg)](https://www.mysql.com/)
[![MongoDB](https://img.shields.io/badge/MongoDB-Atlas-green.svg)](https://www.mongodb.com/cloud/atlas)
[![License](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![Status](https://img.shields.io/badge/Status-Active-success.svg)]()

[Características](#-características-principales) •
[Instalación](#-instalación) •
[Uso](#-uso) •
[Arquitectura](#-arquitectura) •
[Documentación](#-documentación) •
[Contribuir](#-contribuir)

</div>

---

## 📋 Tabla de Contenidos

- [Acerca del Proyecto](#-acerca-del-proyecto)
- [Características Principales](#-características-principales)
- [Tecnologías Utilizadas](#-tecnologías-utilizadas)
- [Requisitos Previos](#-requisitos-previos)
- [Instalación](#-instalación)
- [Configuración](#-configuración)
- [Uso](#-uso)
- [Estructura del Proyecto](#-estructura-del-proyecto)
- [Arquitectura](#-arquitectura)
- [Base de Datos](#-base-de-datos)
- [API y Servicios](#-api-y-servicios)
- [Capturas de Pantalla](#-capturas-de-pantalla)
- [Documentación](#-documentación)
- [Roadmap](#-roadmap)
- [Contribuir](#-contribuir)
- [Licencia](#-licencia)
- [Contacto](#-contacto)
- [Agradecimientos](#-agradecimientos)

---

## 🎯 Acerca del Proyecto

**BOB (Building Optimization Baseline)** es un sistema web integral desarrollado con **Spring Boot** para la gestión profesional de proyectos de construcción. El sistema permite administrar obras, presupuestos, inventarios, avances y recursos de manera eficiente, proporcionando trazabilidad completa y análisis en tiempo real.

### 🌟 Problema que Resuelve

Las empresas constructoras enfrentan desafíos constantes en:
- ❌ Gestión dispersa de información de obras
- ❌ Presupuestos inexactos y desactualizados
- ❌ Control manual de inventarios propenso a errores
- ❌ Falta de evidencia fotográfica geolocalizada
- ❌ Reportes tardíos y poco confiables

### ✅ Solución BOB

BOB centraliza toda la gestión de construcción en una única plataforma:
- ✔️ **APU Multi-Material** con cálculos automáticos
- ✔️ **Inteligencia Artificial** para generación de listas de materiales
- ✔️ **Fotografías Geolocalizadas** con arquitectura híbrida SQL-NoSQL
- ✔️ **Dashboard Ejecutivo** con indicadores en tiempo real
- ✔️ **Reportes Profesionales** exportables a PDF/Excel

---

## 🚀 Características Principales

### 🎨 Módulos del Sistema

| Módulo | Descripción | Estado |
|--------|-------------|--------|
| **👥 Usuarios y Roles** | Gestión de usuarios con control de acceso basado en roles (RBAC) | ✅ Completo |
| **🏗️ Obras** | Administración de proyectos con geolocalización GPS | ✅ Completo |
| **📊 APU Multi-Material** | Análisis de precios unitarios con soporte ilimitado de materiales | ✅ Completo |
| **🤖 Generación con IA** | Integración con DeepSeek para generar listas automáticamente | ✅ Completo |
| **📦 Materiales** | Catálogo maestro de materiales con precios | ✅ Completo |
| **🏭 Inventarios** | Control de stock con entradas/salidas y alertas | ✅ Completo |
| **🚚 Proveedores** | Directorio de proveedores con información comercial | ✅ Completo |
| **👷 Contratistas** | Gestión de contratistas y asignaciones | ✅ Completo |
| **📈 Avances** | Registro de progreso con evidencia fotográfica geolocalizada | ✅ Completo |
| **📸 Fotografías** | Almacenamiento híbrido MySQL + MongoDB Atlas (GridFS) | ✅ Completo |
| **📑 Reportes** | Generación de informes profesionales (PDF, Excel, CSV) | ✅ Completo |
| **📊 Dashboard** | Panel ejecutivo con KPIs y mapas interactivos | ✅ Completo |

### ⭐ Características Diferenciadoras

#### 1️⃣ **APU Multi-Material Avanzado**
```
✨ Soporte ilimitado de materiales por APU
✨ Cálculo automático de costos con porcentajes de desperdicio
✨ Desglose detallado: Materiales + M.O. + Transporte + Misc.
✨ Clonación y versionado de APUs
```

#### 2️⃣ **Inteligencia Artificial Integrada**
```
🤖 API DeepSeek para generación automática de materiales
🤖 Descripción → IA → Lista completa de materiales
🤖 Ahorra hasta 80% del tiempo en creación de APUs
```

#### 3️⃣ **Arquitectura Híbrida SQL + NoSQL**
```
🗄️ MySQL: Datos relacionales y metadatos
🍃 MongoDB Atlas: Archivos binarios (fotografías) con GridFS
📍 Geolocalización automática de fotografías (GPS)
🚀 Optimización de rendimiento y escalabilidad
```

#### 4️⃣ **Geolocalización Total**
```
🗺️ Obras con coordenadas GPS precisas
📸 Fotografías con ubicación exacta de captura
🌍 Visualización en mapas interactivos
📊 Trazabilidad geoespacial completa
```

#### 5️⃣ **Seguridad Robusta**
```
🔐 Spring Security con autenticación y autorización
🔑 Encriptación BCrypt de contraseñas
🛡️ Control de acceso basado en roles (RBAC)
🔒 Protección CSRF, XSS y SQL Injection
📝 Auditoría completa de operaciones
```

---

## 🛠️ Tecnologías Utilizadas

### Backend
- **Java 17** - Lenguaje de programación
- **Spring Boot 3.x** - Framework principal
  - Spring MVC - Arquitectura web
  - Spring Security - Seguridad y autenticación
  - Spring Data JPA - Persistencia con Hibernate
- **Maven** - Gestión de dependencias

### Frontend
- **Thymeleaf** - Motor de templates
- **Bootstrap 5** - Framework CSS responsive
- **JavaScript** - Lógica del cliente
- **HTML5 + CSS3** - Estructura y estilos

### Bases de Datos
- **MySQL 8.0** - Base de datos relacional
  - 28 tablas normalizadas
  - Relaciones complejas optimizadas
- **MongoDB Atlas** - Base de datos NoSQL
  - GridFS para almacenamiento de archivos
  - Chunks de 261120 bytes
  - Geolocalización de fotografías

### Servicios Externos
- **DeepSeek AI** - API de inteligencia artificial
- **Google Maps API** - Mapas y geolocalización (opcional)

### Herramientas de Desarrollo
- **IntelliJ IDEA / Eclipse** - IDE
- **Git & GitHub** - Control de versiones
- **Postman** - Testing de APIs
- **MySQL Workbench** - Gestión de BD
- **MongoDB Compass** - Explorador MongoDB

---

## 📋 Requisitos Previos

Antes de instalar BOB, asegúrate de tener:

```bash
✅ Java JDK 17 o superior
✅ Maven 3.8+
✅ MySQL 8.0 o superior
✅ Cuenta en MongoDB Atlas (gratuita)
✅ Git
✅ Navegador web moderno (Chrome, Firefox, Edge)
```

### Verificar Instalaciones

```bash
# Verificar Java
java -version
# Debe mostrar: java version "17.x.x"

# Verificar Maven
mvn -version
# Debe mostrar: Apache Maven 3.x.x

# Verificar MySQL
mysql --version
# Debe mostrar: mysql Ver 8.0.x

# Verificar Git
git --version
# Debe mostrar: git version 2.x.x
```

---

## 📥 Instalación

### 1. Clonar el Repositorio

```bash
git clone https://github.com/TESoCo/protoBOB2211.git
cd protoBOB2211
```

### 2. Configurar MySQL

```bash
# Conectar a MySQL
mysql -u root -p

# Crear base de datos
CREATE DATABASE protobob CHARACTER SET utf8mb4 COLLATE utf8mb4_unicode_ci;

# Crear usuario (opcional pero recomendado)
CREATE USER 'bob_user'@'localhost' IDENTIFIED BY 'tu_password_seguro';
GRANT ALL PRIVILEGES ON protobob.* TO 'bob_user'@'localhost';
FLUSH PRIVILEGES;

# Salir
EXIT;
```

### 3. Importar Esquema de Base de Datos

```bash
# Opción 1: Desde archivo SQL (si existe)
mysql -u root -p protobob < database/schema.sql

# Opción 2: Hibernate creará las tablas automáticamente
# (configurar spring.jpa.hibernate.ddl-auto=update en application.properties)
```

### 4. Configurar MongoDB Atlas

1. Crear cuenta gratuita en [MongoDB Atlas](https://www.mongodb.com/cloud/atlas)
2. Crear un cluster (tier gratuito M0)
3. Crear base de datos: `mongoBOB`
4. Obtener connection string (URI)
5. Whitelist tu IP o permitir acceso desde cualquier lugar (0.0.0.0/0)

### 5. Configurar Archivo `application.properties`

Crear/editar `src/main/resources/application.properties`:

```properties
# ============================================
# CONFIGURACIÓN DEL SERVIDOR
# ============================================
server.port=8080
spring.application.name=BOB

# ============================================
# CONFIGURACIÓN MYSQL
# ============================================
spring.datasource.url=jdbc:mysql://localhost:3306/protobob?useSSL=false&serverTimezone=UTC&allowPublicKeyRetrieval=true
spring.datasource.username=root
spring.datasource.password=TU_PASSWORD_MYSQL
spring.datasource.driver-class-name=com.mysql.cj.jdbc.Driver

# JPA/Hibernate
spring.jpa.hibernate.ddl-auto=update
spring.jpa.show-sql=false
spring.jpa.properties.hibernate.format_sql=true
spring.jpa.properties.hibernate.dialect=org.hibernate.dialect.MySQL8Dialect

# ============================================
# CONFIGURACIÓN MONGODB ATLAS
# ============================================
spring.data.mongodb.uri=mongodb+srv://usuario:password@cluster.mongodb.net/mongoBOB?retryWrites=true&w=majority
spring.data.mongodb.database=mongoBOB

# ============================================
# CONFIGURACIÓN THYMELEAF
# ============================================
spring.thymeleaf.cache=false
spring.thymeleaf.prefix=classpath:/templates/
spring.thymeleaf.suffix=.html

# ============================================
# CONFIGURACIÓN DE ARCHIVOS (FOTOGRAFÍAS)
# ============================================
spring.servlet.multipart.enabled=true
spring.servlet.multipart.max-file-size=10MB
spring.servlet.multipart.max-request-size=10MB

# ============================================
# CONFIGURACIÓN DE LOGGING
# ============================================
logging.level.root=INFO
logging.level.com.bob=DEBUG
logging.pattern.console=%d{yyyy-MM-dd HH:mm:ss} - %msg%n

# ============================================
# CONFIGURACIÓN API DEEPSEEK (OPCIONAL)
# ============================================
deepseek.api.url=https://api.deepseek.com/v1/chat/completions
deepseek.api.key=TU_API_KEY_AQUI
```

### 6. Instalar Dependencias y Compilar

```bash
# Limpiar y compilar proyecto
mvn clean install

# O solo compilar sin tests
mvn clean install -DskipTests
```

### 7. Ejecutar la Aplicación

```bash
# Opción 1: Con Maven
mvn spring-boot:run

# Opción 2: Ejecutar JAR
java -jar target/bob-1.0.0.jar

# Opción 3: Desde IDE
# Run > Run 'BobApplication' (IntelliJ)
```

### 8. Acceder al Sistema

Abrir navegador y visitar:
```
http://localhost:8080
```

**Credenciales por defecto (crear usuario admin inicial):**
- Usuario: `admin`
- Contraseña: `admin123` (cambiar inmediatamente)

---

## ⚙️ Configuración

### Configuración de DeepSeek AI (Opcional)

Si deseas usar la funcionalidad de IA para generar materiales automáticamente:

1. Obtener API Key en [DeepSeek Platform](https://platform.deepseek.com/)
2. Agregar en `application.properties`:
```properties
deepseek.api.key=sk-xxxxxxxxxxxxxxxxxxxxxxx
```

### Configuración de Email (Recuperación de Contraseña)

```properties
spring.mail.host=smtp.gmail.com
spring.mail.port=587
spring.mail.username=tu_email@gmail.com
spring.mail.password=tu_app_password
spring.mail.properties.mail.smtp.auth=true
spring.mail.properties.mail.smtp.starttls.enable=true
```

---

## 🎮 Uso

### Flujo Básico de Trabajo

#### 1️⃣ **Crear Usuarios**
```
Administrador → Usuarios → Nuevo Usuario
- Asignar rol (Administrador, Supervisor, Operario)
- Configurar permisos
```

#### 2️⃣ **Crear Materiales**
```
Administrador → Materiales → Nuevo Material
- Código, nombre, unidad, precio
- Asociar proveedor
```

#### 3️⃣ **Crear APU**
```
Supervisor → APU → Nuevo APU
- Nombre y unidad de medida
- Agregar múltiples materiales
- Especificar cantidades y desperdicios
- O usar IA para generar automáticamente
```

#### 4️⃣ **Crear Obra**
```
Supervisor → Obras → Nueva Obra
- Información básica
- Coordenadas GPS
- Asociar APUs → Presupuesto automático
```

#### 5️⃣ **Registrar Avances**
```
Operario → Avances → Nuevo Avance
- Seleccionar obra y APU
- Cantidad ejecutada
- Capturar fotos geolocalizadas
```

#### 6️⃣ **Generar Reportes**
```
Supervisor → Reportes
- Seleccionar tipo (Presupuesto, Avances, Inventario)
- Exportar a PDF/Excel
```

### Ejemplos de Uso

#### Crear APU con IA

```java
// Ejemplo desde el frontend
POST /apu/generate-materials
{
  "description": "Placa de concreto 3000 PSI, espesor 10cm"
}

// Respuesta de DeepSeek
{
  "materials": [
    {"name": "Cemento", "quantity": 7, "unit": "bultos"},
    {"name": "Arena", "quantity": 0.5, "unit": "m³"},
    {"name": "Grava", "quantity": 0.7, "unit": "m³"},
    ...
  ]
}
```

---

## 📁 Estructura del Proyecto

```
protoBOB2211/
├── src/
│   ├── main/
│   │   ├── java/
│   │   │   └── com/
│   │   │       └── bob/
│   │   │           ├── config/              # Configuraciones Spring
│   │   │           │   ├── SecurityConfig.java
│   │   │           │   └── MongoConfig.java
│   │   │           ├── controller/          # Controladores MVC
│   │   │           │   ├── UsuarioController.java
│   │   │           │   ├── ObraController.java
│   │   │           │   ├── ApuController.java
│   │   │           │   ├── AvanceController.java
│   │   │           │   └── ...
│   │   │           ├── model/               # Entidades JPA/MongoDB
│   │   │           │   ├── Persona.java
│   │   │           │   ├── Usuario.java
│   │   │           │   ├── Obra.java
│   │   │           │   ├── Apu.java
│   │   │           │   ├── Avance.java
│   │   │           │   ├── Fotodato.java
│   │   │           │   └── ...
│   │   │           ├── repository/          # Repositorios Spring Data
│   │   │           │   ├── UsuarioRepository.java
│   │   │           │   ├── ObraRepository.java
│   │   │           │   ├── ApuRepository.java
│   │   │           │   ├── FotodatoRepository.java
│   │   │           │   └── ...
│   │   │           ├── service/             # Lógica de negocio
│   │   │           │   ├── UsuarioService.java
│   │   │           │   ├── ObraService.java
│   │   │           │   ├── ApuService.java
│   │   │           │   ├── AvanceService.java
│   │   │           │   ├── DeepSeekService.java
│   │   │           │   ├── MongoStorageService.java
│   │   │           │   └── ...
│   │   │           ├── dto/                 # Data Transfer Objects
│   │   │           │   ├── ApuDTO.java
│   │   │           │   ├── ObraDTO.java
│   │   │           │   └── ...
│   │   │           └── util/                # Utilidades
│   │   │               ├── DateUtils.java
│   │   │               └── FileUtils.java
│   │   └── resources/
│   │       ├── templates/                   # Vistas Thymeleaf
│   │       │   ├── index.html
│   │       │   ├── login.html
│   │       │   ├── obra/
│   │       │   │   ├── lista.html
│   │       │   │   ├── crear.html
│   │       │   │   └── detalle.html
│   │       │   ├── apu/
│   │       │   │   ├── lista.html
│   │       │   │   ├── crear.html
│   │       │   │   └── detalle.html
│   │       │   └── ...
│   │       ├── static/
│   │       │   ├── css/
│   │       │   │   └── styles.css
│   │       │   ├── js/
│   │       │   │   └── main.js
│   │       │   └── images/
│   │       └── application.properties       # Configuración principal
│   └── test/                                # Tests unitarios
│       └── java/
│           └── com/
│               └── bob/
│                   ├── service/
│                   └── repository/
├── docs/                                    # Documentación
│   ├── Manual_Tecnico_BOB.docx
│   ├── Manual_Usuario_BOB.docx
│   ├── Plan_Capacitacion_BOB.docx
│   └── images/
├── database/                                # Scripts SQL
│   ├── schema.sql
│   └── sample_data.sql
├── .gitignore
├── pom.xml                                  # Dependencias Maven
├── README.md
└── LICENSE
```

---

## 🏛️ Arquitectura

BOB implementa una **arquitectura en capas** siguiendo el patrón MVC (Model-View-Controller) con Spring Boot:

```
┌─────────────────────────────────────────────┐
│            CAPA DE PRESENTACIÓN             │
│   (Thymeleaf Templates + Bootstrap + JS)   │
└──────────────────┬──────────────────────────┘
                   │
┌──────────────────▼──────────────────────────┐
│           CAPA DE CONTROLADORES             │
│        (Spring MVC Controllers)             │
│  • UsuarioController                        │
│  • ObraController                           │
│  • ApuController                            │
│  • AvanceController                         │
└──────────────────┬──────────────────────────┘
                   │
┌──────────────────▼──────────────────────────┐
│            CAPA DE SERVICIOS                │
│         (Business Logic Layer)              │
│  • UsuarioService                           │
│  • ObraService                              │
│  • ApuService                               │
│  • DeepSeekService (IA)                     │
│  • MongoStorageService                      │
└──────────────────┬──────────────────────────┘
                   │
┌──────────────────▼──────────────────────────┐
│          CAPA DE REPOSITORIOS               │
│      (Spring Data JPA/MongoDB)              │
│  • UsuarioRepository                        │
│  • ObraRepository                           │
│  • ApuRepository                            │
│  • FotodatoRepository (MongoDB)            │
└──────────────────┬──────────────────────────┘
                   │
    ┌──────────────┴──────────────┐
    │                             │
┌───▼────────┐          ┌─────────▼─────┐
│   MySQL    │          │  MongoDB Atlas│
│  (Datos    │          │  (Fotografías │
│Relacionales)│          │   + GridFS)   │
└────────────┘          └───────────────┘
```

### Arquitectura Híbrida SQL + NoSQL

**Ventajas del Enfoque Híbrido:**

| Aspecto | MySQL | MongoDB Atlas |
|---------|-------|---------------|
| **Uso** | Datos estructurados y relacionales | Archivos binarios (imágenes) |
| **Fortaleza** | Integridad referencial, consultas complejas | Escalabilidad horizontal, performance |
| **Ejemplo** | Usuarios, Obras, APUs, Materiales | Fotografías con GridFS |
| **Consultas** | SQL/JPA con joins complejos | Consultas de archivos por ID |

---

## 🗄️ Base de Datos

### Esquema MySQL (28 Tablas)

#### Tablas Principales

```sql
-- Gestión de Usuarios
persona (persona_id, nombres, apellidos, documento, ...)
usuario (usuario_id, username, password_hash, persona_id)
rol (rol_id, nombre, descripcion)
permiso (permiso_id, nombre, modulo, accion)
rol_permiso (rol_id, permiso_id)

-- Gestión de Obras
obra (obra_id, nombre, etapa, fecha_inicio, fecha_fin, latitud, longitud, ...)

-- Gestión de APUs
apu (apu_id, nombre, unidad_medida, descripcion)
caracteristicas_apu (caract_apu_id, apu_id, tipo, descripcion)
materiales_apu (mat_apu_id, apu_id, material_nombre, cantidad, desperdicio, precio_unitario)
valor_apu (valor_apu_id, apu_id, tipo_costo, valor)
apus_obra (apu_obra_id, obra_id, apu_id, cantidad_presupuestada)

-- Gestión de Materiales
materiales (material_id, codigo, nombre, unidad, precio, proveedor_id)
proveedor (proveedor_id, nit, razon_social, contacto, ...)

-- Gestión de Inventarios
inventario (inventario_id, obra_id, nombre)
materiales_inventario (mat_inv_id, inventario_id, material_id, cantidad, fecha_entrada)

-- Gestión de Avances
avance (avance_id, obra_id, apu_id, fecha_registro, observaciones)
cantidad_avance (cant_avance_id, avance_id, cantidad_ejecutada, unidad)
fecha_avance (fecha_avance_id, avance_id, fecha_ejecucion)
fotodato (fotodato_id, avance_id, descripcion, latitud, longitud, fecha_captura)
imagen_fotodato (imagen_id, fotodato_id, mongodb_file_id, filename, content_type)

-- Otros
contratista (contratista_id, nit, razon_social, ...)
```

### Modelo MongoDB

```javascript
// Colección: fs.files (GridFS para fotografías)
{
  "_id": ObjectId("..."),
  "filename": "foto_avance_001.jpg",
  "length": 524288,
  "chunkSize": 261120,
  "uploadDate": ISODate("2025-12-02T10:30:00Z"),
  "metadata": {
    "_contentType": "image/jpeg",
    "avanceId": 123,
    "originalFileName": "foto_obra.jpg",
    "uploadTime": "2025-12-02T10:30:00",
    "coordinates": {
      "latitude": 4.7110,
      "longitude": -74.0721
    }
  }
}

// Colección: fs.chunks (bloques de archivos)
{
  "_id": ObjectId("..."),
  "files_id": ObjectId("..."),
  "n": 0,
  "data": BinData(...)
}
```

### Diagrama ER

```
[Ver diagrama completo en: /docs/database/ER_diagram.png]
```

---

## 🔌 API y Servicios

### Endpoints Principales

#### Autenticación
```http
POST   /login              # Iniciar sesión
POST   /logout             # Cerrar sesión
POST   /recuperar-password # Recuperar contraseña
```

#### Usuarios
```http
GET    /usuarios           # Listar usuarios
GET    /usuarios/{id}      # Ver detalle
POST   /usuarios           # Crear usuario
PUT    /usuarios/{id}      # Actualizar usuario
DELETE /usuarios/{id}      # Eliminar usuario
```

#### Obras
```http
GET    /obras              # Listar obras
GET    /obras/{id}         # Ver detalle
POST   /obras              # Crear obra
PUT    /obras/{id}         # Actualizar obra
DELETE /obras/{id}         # Eliminar obra
GET    /obras/mapa         # Ver obras en mapa
```

#### APUs
```http
GET    /apus               # Listar APUs
GET    /apus/{id}          # Ver detalle
POST   /apus               # Crear APU
PUT    /apus/{id}          # Actualizar APU
DELETE /apus/{id}          # Eliminar APU
POST   /apus/clonar/{id}   # Clonar APU
POST   /apus/generate-ia   # Generar con IA
```

#### Avances
```http
GET    /avances            # Listar avances
GET    /avances/{id}       # Ver detalle
POST   /avances            # Crear avance
POST   /avances/fotos      # Subir fotografías
GET    /avances/{id}/fotos # Ver galería
```

#### Reportes
```http
GET    /reportes/presupuesto/{obraId}?format=pdf
GET    /reportes/avances/{obraId}?format=excel
GET    /reportes/inventario/{inventarioId}?format=csv
```

### Integración DeepSeek AI

```java
// Ejemplo de llamada a la API
@Service
public class DeepSeekService {
    
    @Value("${deepseek.api.key}")
    private String apiKey;
    
    public List<MaterialDTO> generateMaterials(String description) {
        // Construir prompt
        String prompt = "Genera una lista de materiales para: " + description;
        
        // Llamar API DeepSeek
        HttpHeaders headers = new HttpHeaders();
        headers.setBearerAuth(apiKey);
        
        // Procesar respuesta
        // ...
        
        return materials;
    }
}
```

---

## 📸 Capturas de Pantalla

### Dashboard Principal
![Dashboard](docs/screenshots/dashboard.png)
*Panel ejecutivo con indicadores clave y mapa de obras*

### Creación de APU Multi-Material
![APU](docs/screenshots/apu-crear.png)
*Interfaz para crear APU con múltiples materiales y cálculos automáticos*

### Generación con IA
![IA](docs/screenshots/ia-generate.png)
*DeepSeek generando lista de materiales automáticamente*

### Registro de Avances
![Avances](docs/screenshots/avances.png)
*Registro de progreso con fotografías geolocalizadas*

### Mapa de Obras
![Mapa](docs/screenshots/mapa-obras.png)
*Visualización geoespacial de proyectos activos*

### Reporte PDF
![Reporte](docs/screenshots/reporte-pdf.png)
*Reporte profesional de presupuesto exportado*

---

## 📚 Documentación

La documentación completa del proyecto está disponible en la carpeta `/docs`:

| Documento | Descripción | Páginas |
|-----------|-------------|---------|
| [Manual Técnico](docs/Manual_Tecnico_BOB.docx) | Arquitectura, instalación, configuración, estructura de BD | 50+ |
| [Manual de Usuario](docs/Manual_Usuario_BOB.docx) | Guía paso a paso para usuarios finales | 40+ |
| [Plan de Capacitación](docs/Plan_Capacitacion_BOB.docx) | Programa de formación de usuarios | 35+ |
| [Requerimientos](docs/Requerimientos_BOB.md) | 119 HU funcionales + 42 RNF | - |
| [API Documentation](docs/API.md) | Endpoints y ejemplos de uso | - |

### JavaDoc

Generar documentación JavaDoc:

```bash
mvn javadoc:javadoc
# La documentación se genera en: target/site/apidocs/
```

---

## 🗺️ Roadmap

### ✅ Versión 1.0 (Actual)
- [x] Sistema completo de gestión de obras
- [x] APU multi-material con IA
- [x] Arquitectura híbrida SQL + NoSQL
- [x] Fotografías geolocalizadas
- [x] Reportes profesionales
- [x] Dashboard ejecutivo
- [x] Control de acceso RBAC

### 🚧 Versión 1.1 (En Planificación)
- [ ] App móvil nativa (Android/iOS)
- [ ] API REST pública documentada
- [ ] Integración con sensores IoT
- [ ] Dashboard con gráficos avanzados (Chart.js)
- [ ] Notificaciones push
- [ ] Exportación a formatos CAD

### 🔮 Versión 2.0 (Futuro)
- [ ] Machine Learning para predicción de costos
- [ ] Realidad Aumentada (AR) para visualización
- [ ] Blockchain para trazabilidad
- [ ] Integración con drones para inspección
- [ ] Módulo de contabilidad completo
- [ ] Multi-idioma (i18n)

---

## 🤝 Contribuir

¡Las contribuciones son bienvenidas! Si deseas contribuir al proyecto:

### Proceso de Contribución

1. **Fork** el repositorio
2. **Crea** una rama para tu feature (`git checkout -b feature/AmazingFeature`)
3. **Commit** tus cambios (`git commit -m 'Add: Amazing Feature'`)
4. **Push** a la rama (`git push origin feature/AmazingFeature`)
5. **Abre** un Pull Request

### Convenciones de Código

- Seguir estilo Java estándar (Google Java Style Guide)
- Documentar métodos públicos con JavaDoc
- Escribir tests unitarios para nueva funcionalidad
- Commits descriptivos en español o inglés

### Reportar Bugs

Usa la sección de [Issues](https://github.com/TESoCo/protoBOB2211/issues) e incluye:
- Descripción clara del problema
- Pasos para reproducir
- Comportamiento esperado vs. actual
- Screenshots (si aplica)
- Versión de Java, navegador, OS

---

## 📄 Licencia

Este proyecto está licenciado bajo la **Licencia MIT** - ver el archivo [LICENSE](LICENSE) para más detalles.

```
MIT License

Copyright (c) 2025 Andrés, Jose, Angel y Andrés [TESoCo]

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

[Ver LICENSE completo]
```

---

## 👤 Contacto

**Andrés** - Desarrollador Principal

- GitHub: [@TESoCo](https://github.com/TESoCo)
- Email: carta.v.devhouse.@gmail.com
- LinkedIn: https://www.linkedin.com/in/jos%C3%A9-t-76ba22a2

**Proyecto:** [https://github.com/TESoCo/protoBOB2211](https://github.com/TESoCo/protoBOB2211)

---

## 🙏 Agradecimientos

Especial agradecimiento a:

- **Spring Framework Team** - Por el excelente framework
- **MongoDB** - Por la plataforma Atlas
- **DeepSeek AI** - Por la API de inteligencia artificial
- **Bootstrap Team** - Por el framework CSS
- **Thymeleaf** - Por el motor de templates
- **Comunidad Open Source** - Por las librerías y recursos

---

## 📊 Estadísticas del Proyecto

![GitHub repo size](https://img.shields.io/github/repo-size/TESoCo/protoBOB2211)
![GitHub language count](https://img.shields.io/github/languages/count/TESoCo/protoBOB2211)
![GitHub top language](https://img.shields.io/github/languages/top/TESoCo/protoBOB2211)
![GitHub last commit](https://img.shields.io/github/last-commit/TESoCo/protoBOB2211)

---

<div align="center">

**⭐ Si este proyecto te resultó útil, considera darle una estrella en GitHub ⭐**

Hecho con ❤️ y ☕ por [Jose Taylor, Angel Rico, Andres Velandia y Andres Calderon](https://github.com/TESoCo)

**[⬆ Volver arriba](#-bob---building-optimization-baseline)**

</div>
