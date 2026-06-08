# Conferencia JAS 2026 — Grid TIS Logístico 🗓️

Este repositorio contiene el núcleo del sistema **Grid TIS (Time Interval System)** para la **Conferencia JAS 2026**. Es una aplicación interactiva en **React** diseñada para la planificación de horarios y el despliegue operativo en tiempo real de subcomités y matrimonios de apoyo.

## 🚀 Características Clave

- **Matriz de Tiempos Dinámica:** Cuadrícula inteligente que segmenta el día en intervalos de 30 minutos desde las 07:00 hasta las 03:00 del día siguiente.
- **Lógica de Actividades Paralelas:** Algoritmo dinámico (`computeTracks`) que calcula colisiones en el horario y apila visualmente las subtareas en carriles paralelos libres.
- **Ruptura de Puntos de Control (`getBreakpoints`):** Sistema adaptativo que recalculación las celdas asignables del personal cuando las actividades en paralelo poseen horas de inicio o fin cruzadas.
- **Panel Operativo Lateral:** Cuadro de mandos en tiempo real para verificar la cobertura de actividades, personal libre y balance por comités.
- **Persistencia Reactiva:** Configurado estructuralmente para gestionar estados y mutaciones mediante Callbacks limpios.

## 📂 Subcomités Incorporados

La aplicación gestiona los flujos de personal de los siguientes frentes:
- **COORD:** Coordinadores
- **M.APY:** Matrimonio de Apoyo
- **M.MIS:** Matrimonios Misioneros
- **B.ORG:** Brilla y Organiza (Logística y Operaciones)
- **B.CEL:** Brilla y Celebra
- **B.PRE:** Brilla en su Presencia
- **B.SIR:** Brilla Sirviendo
- **B.COM:** Brilla y Comparte

## 🛠️ Instalación y Configuración

1. Clona el repositorio:
   ```bash
   git clone [https://github.com/TU_USUARIO/TU_REPOSITORIO.git](https://github.com/TU_USUARIO/TU_REPOSITORIO.git)
