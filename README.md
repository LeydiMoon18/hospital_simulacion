# hospital_simulacion
Simulación de sistema hospitalario en Python usando concurrencia, paralelismo y asincronía.

# 🏥 Simulación de un Sistema Hospitalario

Este proyecto simula el funcionamiento de un sistema hospitalario automatizado mediante paradigmas de programación **concurrente**, **paralela** y **asíncrona** en Python.

## 🎯 Objetivo

Aplicar y diferenciar los paradigmas de programación paralela, concurrente y asíncrona mediante la simulación de un sistema hospitalario automatizado. El sistema representa un entorno realista que requiere procesamiento distribuido de tareas en distintos tiempos y recursos.

## ⚙️ Tecnologías utilizadas

- `threading` – Registro de pacientes y control de recursos
- `asyncio` – Diagnóstico automático con latencia simulada
- `multiprocessing` – Seguimiento y alta médica en paralelo
- `queue`, `semaphore`, `datetime` – Control de flujos y tiempos

## 🧪 Etapas del sistema

1. **Registro** – Pacientes se registran concurrentemente (con semáforo)
2. **Diagnóstico** – Diagnóstico asíncrono que asigna prioridad
3. **Asignación de recursos** – Solo pacientes prioritarios acceden a camas y doctores
4. **Seguimiento y alta** – Procesamiento paralelo por `multiprocessing`

## 📁 Archivos principales

- `Práctica de concurrencia y paralelismo.ipynb`: Implementación completa y ejecutable en Google Colab
- `JiménezPinedaLeydiMonserratPracticaHospital.pdf`: Informe detallado de la práctica

## ✅ Autor

Leydi Monserrat Jiménez Pineda  
FES Acatlán – UNAM  
Programación Paralela y Concurrente

