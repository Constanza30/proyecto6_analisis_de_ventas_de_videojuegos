# 📊 Proyecto 6. Análisis de Ventas de Videojuegos

# 🧠 Descripción del proyecto
Este proyecto tiene como objetivo identificar los factores que determinan el éxito comercial de un videojuego, con el fin de apoyar la planificación de campañas publicitarias para el año 2017.
El análisis se basa en datos históricos de ventas, plataformas, géneros, regiones, calificaciones y clasificaciones ESRB.

--- 

## 📂 Preparación de datos
- Limpieza de valores ausentes, duplicados y atípicos
- Conversión de tipos de datos
- Creación de variables agregadas (ventas totales)
- Filtrado estratégico de datos desde 2011 en adelante, considerando ciclos de vida de plataformas

--- 

## 📈 Análisis exploratorio clave
🎮 Plataformas
- Identificación de plataformas activas y su ciclo de vida
- Análisis de tendencias de ventas anuales
- Plataformas potencialmente rentables para 2017:
    PS4 . Xbox One . Nintendo 3DS . PC (por estabilidad histórica)

--- 

## 🔄 Juegos multiplataforma
- Identificación de 796 juegos lanzados en más de una plataforma
- Las plataformas con mayor presencia multiplataforma:
    PS3 . Xbox 360 . PS4 . PC . Xbox One
- Las ventas varían significativamente entre plataformas, siendo mayores en aquellas con mayor penetración de mercado.

--- 

### 🕹️ Géneros
- Por volumen de juegos: 
    Acción . Rol . Aventura . Deportes
- Por ventas totales: 
    Acción . Shooter . Rol . Deportes
- Los shooters generan altas ventas con menos títulos, lo que indica alta rentabilidad por juego.

--- 

### 🌍 Perfil de usuario por región
1. Norteamérica
  - Plataformas líderes: Xbox 360, PS3, PS4
  - Géneros preferidos: Acción y Shooter
  - Clasificación ESRB dominante: M (Mature)

2. Europa
  - Plataformas líderes: PS3 y PS4
  - Preferencias similares a Norteamérica
  - Clasificación ESRB dominante: M

3. Japón
  - Plataforma líder: Nintendo 3DS
  - Género principal: Role-Playing
  - Clasificación ESRB dominante: E (Everyone)

Japón muestra preferencias claramente distintas frente a Occidente, tanto en plataformas como en géneros.

--- 

## 🧪 Pruebas de hipótesis estadísticas
### Hipótesis 1
*Ho*: Las calificaciones promedio de usuarios en Xbox One y PC son iguales
  -  Prueba: t de Student
  - Resultado: No se rechaza Ho
  - Conclusión: Las calificaciones son estadísticamente similares

### Hipótesis 2
*H1*: Las calificaciones promedio de usuarios en juegos de Acción y Deportes son diferentes
  - Prueba: t de Student
  - Resultado: Se rechaza H1
  - Conclusión: Existen diferencias significativas entre ambos géneros

--- 

### ✅ Conclusiones generales
- El mercado se ha concentrado en menos plataformas y géneros, priorizando rentabilidad sobre volumen.
- PS4, Xbox One y 3DS son las plataformas más prometedoras para campañas en 2017.
- Las calificaciones de usuarios y críticos influyen en las ventas, aunque no de forma determinante.
- Los géneros Acción, Shooter y Rol concentran la mayor parte de las ventas.
- Las preferencias regionales son clave para una estrategia de marketing efectiva.

--- 

## 🛠️ Herramientas y tecnologías
- Python
- Pandas / NumPy
- Matplotlib / Seaborn
- SciPy (pruebas estadísticas)
- Jupyter Notebook
