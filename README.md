![Tests](https://github.com/facucasella/practico-tests-node/actions/workflows/tests.yml/badge.svg)

# Práctico autoguiado: Tests unitarios con Node.js y GitHub

Repositorio del trabajo práctico de pruebas unitarias utilizando el test runner nativo de Node.js (`node:test` y `node:assert/strict`) e Integración Continua con GitHub Actions.

## Respuesta del Ejercicio 4
**¿Por qué el compañero no encontró el bug probando solo con 40000 y 60000?**
Porque no probó el valor límite exacto (`50000`), donde el operador `>` excluía erróneamente a `$50.000` del descuento del 10 % en lugar de usar `>=`.
