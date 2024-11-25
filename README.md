# Proyecto Angular: **Sistema de Gestión Empresarial**
Realizado por: Guzmán Vite Adamaris Vite Adamaris Yareth Guadalupe
## Introducción
Este proyecto es una aplicación web desarrollada en Angular, enfocada en optimizar la administración de negocios mediante funcionalidades modernas y herramientas digitales. Integra características como inicio de sesión, visualización de datos en tablas dinámicas provenientes de una API, y visualización de perfil de usuario en una interfaz amigable y eficiente.

## Objetivo
Proporcionar una plataforma versátil y accesible para:
- Gestionar el acceso de usuarios mediante un sistema de inicio de sesión seguro, donde obtuve los datos de la API https://api.escuelajs.co/api/v1/users.
- Interacción con la información a través de tablas dinámicas alimentadas desde una API (https://api.escuelajs.co/api/v1/products).

---

## Arquitectura del Proyecto

### 1. **Núcleo de la Aplicación**
El archivo principal, `main.ts`, sirve como punto de entrada para la inicialización de la aplicación Angular, mientras que `index.html` actúa como plantilla base para la estructura HTML.

### 2. **Componentes Principales**

#### Módulo de Negocios (`bussiness`)
Este módulo alberga componentes específicos para funcionalidades esenciales:
- **`login`**: Proporciona un formulario de autenticación para permitir acceso seguro al sistema.
- **`dashboard`**: Representa el panel principal con una vista general de datos relevantes del negocio.
- **`tablas`**: Permite gestionar y visualizar datos provenientes de una API en formato tabular.

#### Módulo Compartido (`shared`)
Incluye elementos reutilizables que mejoran la consistencia visual y funcional de la aplicación:
- **`menu`**: Barra de navegación superior que facilita el acceso a las principales funcionalidades.
- **`sidebar`**: Barra para moverse de forma organizada entre secciones.

### 3. **Rutas**
El enrutamiento de la aplicación, configurado en `app.routes.ts`, define cómo los usuarios navegan entre componentes. Ejemplo:
```typescript
{ path: 'perfil', component: PerfilComponent },
{ path: 'tablas', component: TablasComponent },
```

## Estilos
El diseño visual está controlado por:
- **`styles.css`**: Archivo principal para estilos globales.
- **`custom-theme.scss`**: Tema personalizado que se adapta a la identidad visual del proyecto.

---

## Funcionalidades Clave

### Inicio de Sesión
- Autenticación de usuarios mediante validación de credenciales.

### Director del Panel
- Acceso rápido a información clave desde el `dashboard`.

### Gestión de Usuarios
- Visualización de detalles personales en un perfil accesible y organizado.

### Integración con API
- Uso de una API para obtener datos dinámicos y presentarlos en tablas interactivas.

### Navegación Intuitiva
- **Menú superior**: Para acceder fácilmente a las funciones principales.

---

## Requisitos Técnicos
- **Node.js**: Para manejar dependencias y ejecutar scripts del proyecto.
- **Angular CLI**: Para desarrollar, compilar y servir la aplicación.

---

## Guía de Instalación

1. **Clonar el repositorio**:
   ```
   git clone <url-del-repositorio>
   ```
1. **Instalar dependencias**:
```
npm install
```
3. **Iniciar la aplicación**:
```
ng serve
```
4. **Abrir navegador**:
Abrir tu navegador e ingresar a: http ://localhost :4200

## **Pruebas**:
### Login
![image](https://github.com/user-attachments/assets/24c365b6-f645-488b-b89f-30a7c1f85ab4)

### Inicio
![image](https://github.com/user-attachments/assets/9bf39912-47ac-4484-a39d-329fd82036e2)

### Menu
![image](https://github.com/user-attachments/assets/ac28f6fe-9b78-4d2f-acf4-af384ae33578)

### Tabla
![image](https://github.com/user-attachments/assets/df1fef78-6e52-447c-8ba4-c5063ce388a1)

### Paginación
![image](https://github.com/user-attachments/assets/8b605660-fd5d-4522-afef-25cb35726a00)

### Botones
![image](https://github.com/user-attachments/assets/9ecd30a6-eaeb-4174-afd4-0b11aca5bd69)

### Salir
![image](https://github.com/user-attachments/assets/98515341-45ee-4c92-8b59-1b62e6ea9fe6)


### End
