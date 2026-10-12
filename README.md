# Actividad-3-ENFOQUE-MODULAR-Y-DISE-O-TOP-DOWN
## Proyecto Integrador Anual - LPR 2026

* **Institución:** E.E.S.T. N.º 1 "Eduardo Ader" - Vicente López
* **Curso:** 5° Año 3° (A-B)
* **Materia:** Laboratorio de Programación (LPR)
* **Profesor:** Prof. York
* **Actividad:** Actividad 3: Enfoque Modular y Diseño Top-Down (Cálculo de Área Modular)

---

## 📝 Descripción del Proyecto
Este software implementa una solución de ingeniería estructurada utilizando la metodología **Top-Down** para resolver el cálculo geométrico del área de un círculo. El programa fragmenta la problemática lógica mediante funciones modulares independientes en C++ e incorpora filtros de consistencia rígidos para impedir el procesamiento de magnitudes físicas inexistentes, renderizando una diana de tiro en gráficos de caracteres ASCII según la escala de la RAM.

## 👥 Integrantes (Grupo N.º 3)
* **Zacarias, Gabriel** - `[Rol: Ingeniería de Software / Programación C++]`
* **Mojica, Sofia** - `[Rol: Análisis de Algoritmos / Pruebas de Modulación]`
* **De Armas, Leonel** - `[Rol: Documentación Técnica / Informe PDF APA]`
* **Roberts, Mateo** - `[Rol: Control de Versiones / Arquitectura de Git]`

---

## 🛠️ Requisitos e Instalación
1. Contar con el compilador **MinGW (GCC/G++)** mapeado de manera global en las variables de entorno (**PATH**).

### ⬇️ Clonar el repositorio estructurado desde la terminal de VS Code:
```bash
git clone https://github.com/Ailuna77/Actividad-3-ENFOQUE-MODULAR-Y-DISEÑO-TOP-DOWN.git
```

### 📂 Posicionarse en el directorio raíz correspondiente a la práctica:
```bash
cd calculoarea
```

---

## 🏃 Ejecución
La compilación guiada por el flujo de desarrollo se ejecuta en la terminal **PowerShell** interna con los siguientes comandos:

### 1. Fase de Compilación (Enlace Modular)
Genera el binario ejecutable dentro del directorio de fuentes:
```powershell
g++ src/main.cpp -o src/calculoarea.exe
```

### 2. Fase de Lanzamiento
Ejecuta el sistema interactivo en entorno Windows:
```powershell
.\src\calculoarea.exe
```

---

## 🗂️ Estructura Obligatoria del Repositorio

```text
calculoarea/
├── .gitignore                      <-- Exclusiones de Git para configuraciones locales (.vscode)
├── LICENSE                         <-- Licencia MIT del proyecto escolar
├── README.md                       <-- Portada técnica del proyecto (Este archivo)
├── docs/                           <-- Carpeta exclusiva para documentación
│   └── InformeProyectoCALCULOAREA.pdf <-- ENTREGABLE (Informe final con normas APA v7)
├── src/                            <-- Carpeta para los códigos fuente del proyecto
│   └── main.cpp                    <-- Código fuente modular adaptado en C++
└── capturas/                       <-- Evidencias locales de validación de sistema (.png)
    ├── compilacion_area.png        <-- Captura de la terminal compilando y corriendo el programa
    └── diagrama_flujo.png          <-- Esquema analógico/digital del flujo lógico modular
```
