# Práctica RA5 · a+b — Datos e información

## 1) Caso
- Sistema: Plataforma de Streaming
- Contexto: Un usuario consume contenido (series y películas) y la plataforma recoge datos para mejorar recomendaciones y experiencia.

## 2) Datos
- ID del usuario
- Hora de inicio de sesión
- Serie/película reproducida
- Tiempo de visualización
- Dispositivo utilizado (móvil, TV, ordenador)
- Ubicación aproximada
- Valoraciones

## 3) Información
- Series más populares en una región
- Contenido recomendado para un usuario según sus gustos
- Horas de mayor uso de la plataforma
- Tasa de abandono de una serie

## 4) Diferencia
- Dato: Es un valor aislado, sin contexto (ejemplo: el tiempo de un usuario viendo una serie)

- Información: Es el resultado de analizar varios datos para obtener un resultado relacionado a los datos (ejemplo: los usuarios suelen dejar de ver la seria en la temporada 3)

## 5) Ciclo del dato
- Captura: Se registran acciones del usuario al usar la app
- Almacenamiento: Los datos se guardan en bases de datos
- Procesamiento: Se organizan y filtran los datos
- Análisis: Se aplican algoritmos para encontrar patrones
- Uso: Se generan recomendaciones y decisiones de negocio
- Eliminación: Se borran o anonimizan datos antiguos o innecesarios

## 6) Aplicación
- Decisiones:
  -- Qué series producir o cancelar
  -- Qué contenido recomendar a cada usuario
  -- En qué horarios lanzar nuevos contenidos
- Valor:
  -- Mejora la experiencia del usuario
  -- Aumenta el tiempo de uso de la plataforma
  -- Incrementa ingresos y fidelización

## 7) Tabla
| Dato | Información |
|------|-------------|
| Usuario vio 45 min de una serie | La serie tiene alto engagement |
| Usuario usa móvil | Preferencia por consumo móvil |
| Hora: 22:00 | Pico de uso nocturno |
| Usuario abandona en episodio 1 | Contenido poco atractivo |
| Valoración negativa | Baja satisfacción del usuario |

## 8) Diagrama
```
Usuario
   ↓
Interacción (clicks, reproducciones, valoraciones)
   ↓
App (frontend)
   ↓
API / Servidor
   ↓
Captura de datos
   ↓
Base de datos (almacenamiento)
   ↓
Procesamiento (limpieza, filtrado, organización)
   ↓
Análisis (algoritmos, machine learning)
   ↓
Generación de información (patrones, métricas)
   ↓
Sistema de recomendaciones
   ↓
Decisiones (contenido sugerido, producción, marketing)
   ↓
Usuario (recibe contenido personalizado)
```
## 9) Problemas
- Problema 1: Datos incompletos (usuarios que no valoran contenido)
- Solución 1: Inferir preferencias mediante comportamiento (IA)
- Problema 2: Datos erróneos (duplicados o mal registrados)
- Solución 2: Aplicar limpieza y validación de datos

## 10) Fuente
- Enlace: https://www.ibm.com/think/topics
