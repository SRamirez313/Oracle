# Oracle
Proyecto para Lenguaje de Base de Datos

# 🎬 Sistema Web de Gestión Integral para un Cine

> Proyecto académico (prototipo funcional). Los datos utilizados son de prueba.

## ✨ Funcionalidades principales

**Módulo de clientes**
- Registro e inicio de sesión con contraseñas protegidas mediante hash
- Consulta de cartelera y filtrado de funciones por película, sede, horario y formato (2D/3D)
- Selección interactiva de asientos según el mapa de la sala
- Compra de alimentos y snacks por categorías
- Aplicación de códigos promocionales
- Pago de la orden y comprobante digital

**Módulo administrativo**
- Gestión de películas, salas, asientos y productos de la dulcería
- Programación de funciones (película, sala, horario, idioma y formato)
- Administración de promociones (código, porcentaje y vigencia)

## 🗄️ Base de datos

Modelo relacional en **Oracle** con 15 tablas: `CINE`, `SALA`, `ASIENTO`, `PELICULA`, `GENERO`, `PELICULA_GENERO`, `FUNCION`, `CLIENTE`, `ORDEN`, `BOLETO`, `PAGO`, `PROMOCION`, `ALIMENTO`, `CATEGORIAALIMENTO` y `COMPRAALIMENTO`.

La restricción única sobre `(ID_FUNCION, ID_ASIENTO)` en `BOLETO` garantiza que un asiento no se venda dos veces para la misma función.

## 🚫 Fuera del alcance

Pasarelas de pago reales, aplicaciones móviles nativas, contabilidad o nómina, integración con distribuidores de películas, hardware físico (lectores QR, impresoras de tickets) y reportes avanzados.

## 🛠️ Tecnologías

- Base de datos: Oracle
- Backend: _por definir_
- Frontend: _por definir_
