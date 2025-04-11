# ⚙️ AppEficienciaIndustrial

Bienvenido a **AppEficienciaIndustrial**, una aplicación iOS desarrollada en Swift con arquitectura **MVVM** para medir la eficiencia de producción por minuto en entornos industriales. 🏭📈

Esta app permite a las empresas registrar en tiempo real la cantidad de productos fabricados, evaluar el rendimiento frente a metas establecidas y generar reportes para optimizar la toma de decisiones en el área de producción.

---

## 📌 Índice

- [📖 Descripción](#-descripción)
- [📱 Interfaces de Usuario](#-interfaces-de-usuario)
- [📂 Estructura del Proyecto](#-estructura-del-proyecto)
- [🔧 Tecnologías Usadas](#-tecnologías-usadas)
- [📸 Recursos](#-recursos)
---

## 📖 Descripción

**AppEficienciaIndustrial** fue creada con el propósito de facilitar el monitoreo de procesos productivos en tiempo real. Está orientada a operarios, supervisores y gerentes que buscan mejorar el control y la eficiencia del flujo de trabajo.

### 🎯 Funcionalidades principales:
✅ Registro por minuto de productos fabricados  
✅ Comparación contra metas de producción  
✅ Cálculo automático de eficiencia por minuto, hora y turno  
✅ Visualización gráfica de rendimiento  
✅ Historial de datos y generación de reportes  
✅ Interfaz intuitiva y adaptable al flujo de trabajo industrial

---

## 📱 Interfaces de Usuario

La app cuenta con pantallas funcionales y simples para facilitar el uso dentro del entorno de trabajo industrial:

### 📊 Dashboard de Producción

<p align="center">
  <img src="Images/Dashboard.gif" alt="Dashboard de Producción" width="300" height="400" />
</p>

---

### ⏱️ Registro de Producción por Minuto

<p align="center">
  <img src="Images/Registro.gif" alt="Registro por Minuto" width="300" height="400" />
</p>

---

### 📈 Visualización de Eficiencia

<p align="center">
  <img src="Images/Eficiencia.gif" alt="Gráfico de Eficiencia" width="300" height="400" />
</p>

---

## 📂 Estructura del Proyecto

La aplicación sigue una estructura organizada basada en **MVVM**:


```plaintext
UAMCourses/
├── AudioManager/           
│
├── Extensiones/           
│
├── Models/
│
├── Networking/           
│
├── Persistance/
│
├── Resources/              # Almacena todo los archivos en formato mov, mp3 y static
│   ├── Mulish              # Almacena todos los tipos de letra de la fuente Mulish        
│
├── ViewModels/              
│
├── Views/
│   ├── Courses             # Almacena el Home Page de los cursos 
│   ├── Create              # Almacena la Vista para añadir cursos
│   ├── DetailView          # Almacena la Vista Previa y Editor de Cursos
│   ├── Extra               # Almacena el controlador del CircularProgressBar
│   ├── FavoriteCourses     # Almacena el controlador y la vista de Mis Favoritos
│   ├── Filter              # Almacena la controlador y vista del filtro inicial de los cursos de interes del usuario
│   ├── Launcher            # Almacena el controlador y vista del Launcher
│   ├── Login               # Almacena el controlador y vista del Inicio de Sesion
│   ├── Onbording           # Almacena los Onboardings Iniciales de la Aplicacion
│   ├── Register            # Almacena el controlador y vista del Registro de Usuarios
│   ├── Settings            # Almacena los controladores y las vistas de Ajustes│
└── README.md                 # Documentación principal del proyecto

```



---

## 🔧 Tecnologías Usadas

- **Swift** 🚀  
- **UIKit** 🎨  
- **MVVM Architecture** 🧠  
- **UserDefaults** 💾  
- **Charts** 📊  
- **AutoLayout & Constraints adaptables** 📱  

---

## 👥 Equipo de Desarrollo

- **[Tu Nombre]** - Desarrollador/a iOS, Diseñador/a de Interfaces, Documentador/a  

---

## 📸 Recursos

- 🎥 [`Registro.mov`](Images/Registro.mov) (Demostración del registro de producción)  
- 🎥 [`Dashboard.mov`](Images/Dashboard.mov) (Vista general del sistema)  
- 🎥 [`Graficas.mov`](Images/Graficas.mov) (Visualización de datos en tiempo real)

