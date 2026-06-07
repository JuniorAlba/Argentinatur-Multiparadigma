# Sistema de Transporte Turístico — Tres Paradigmas de Programación

Implementación del mismo dominio de negocio (un sistema de gestión de viajes turísticos por
las sierras de Córdoba) resuelto en tres paradigmas de programación distintos:
funcional, lógico y orientado a objetos.

## ¿Qué hace?

Modela un sistema de transporte turístico llamado "ArgentinaTur" que gestiona viajes entre
localidades de las sierras cordobesas (desde Córdoba Capital hasta Capilla del Monte).
Según el paradigma, resuelve problemas como:

- **Consultar** itinerarios, precios y horarios disponibles
- **Calcular** el costo de un viaje entre dos localidades
- **Repartir** costos entre pasajeros que comparten tramos
- **Gestionar** reservas, ventas y servicios de transporte

## Los tres paradigmas

### 🟣 Funcional (Racket)
Modela el itinerario como listas anidadas. Implementa consultas de horarios, cálculo de
precios entre tramos, y validación de disponibilidad usando funciones puras y recursión.

### 🔵 Lógico (Prolog)
Define localidades, tramos y costos como hechos. Construye reglas para calcular rutas
completas, identificar tramos compartidos entre pasajeros, y repartir costos
proporcionalmente usando inferencia lógica.

### 🟢 Orientado a Objetos (Python)
Diseña clases como `Servicio`, `Reserva`, `Pasajero`, `Itinerario` y `Venta`. Implementa
un sistema completo de gestión con reservas con validación temporal, reportes de ingresos
y consulta de disponibilidad de asientos.

## Tecnologías

| Paradigma | Lenguaje | Archivo principal |
|---|---|---|
| Funcional | Racket | `tp_funcional/tp.rkt` |
| Lógico | SWI-Prolog | `tp_logico/tp_logico.pl` |
| POO | Python 3 | `tp_poo/argentur.py` + módulos |

## Autores

Albarenque Junior · Godoy Matías · Lencina Federico · Palacios Angel

*Ingeniería en Informática - FICH, UNL*
