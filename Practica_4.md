# Práctica 4. Gestión Avanzada de Ramas y Resolución de Conflictos

### Parte 0 y 1: Fase Base y Desarrollo en Paralelo
*Preparacion del entorno, creacion de ramas, commits correspondientes y fusion inicial.*
- ![Fase base](captura_1.png)
- ![Creacion ramas](Captura%desde%2026-10-26%08-33-58.png)
- ![Desarrollo ramas](Captura%desde%2026-10-26%08-37-42.png)
- ![Fusiones sin conflicto](Captura%desde%2026-10-26%08-42-05.png)
- ![Consolidacion y limpieza](Captura%desde%2026-10-26%08-43-40.png)

### Parte 2: Resolución del Conflicto
*Conflicto modificando la misma linea en `main` y `rediseño`, visualizacion de las marcas de Git.*
- ![Divergencia en rediseño](Captura%desde%2026-10-26%08-45-18.png)
- **Momento del conflicto:**
  ![Conflicto de fusion](Captura%desde%2026-10-26%09-10-47.png)
- **Estado del archivo con las marcas de Git:**
  ![Marcas de conflicto](Captura%desde%2026-10-26%09-11-18.png)

### Parte 3: Visualización del Historial
*Comandos de resolucion del conflicto y salida del comando `git log --oneline --graph --all` mostrando el arbol completo.*
- **Resolucion y arbol del historial:**
  ![Historial final](Captura%desde%2026-10-26%09-25-27.png)

---

## 2. Reflexión Teórica

### ¿Por qué ocurrió el conflicto en la PARTE 3 y por qué no ocurrió en la PARTE 2?
En la parte 3 ocurrio un conflicto porque se modifico exactamente la misma linea dentro del mismo archivo, pero en dos ramas diferentes.
Mientras que en la parte 2 no ocurrio nada porque se realizo las modificaciones en archivos diferentes y nuevos.

### Al ejecutar `git switch main` en la PARTE 3.2, ¿qué ocurrió con los archivos de tu directorio de trabajo?
Lo que ocurrio fue que se actualizo automaticamente para reflejar el estado de los archivos tal y como estaban guardados en la rama main.
