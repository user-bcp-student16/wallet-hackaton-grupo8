# Contrato para agentes

1. Analiza el flujo completo.
2. Conserva el contrato.
3. Crea pruebas de caracterización antes de refactorizar persistencia o token.
4. No silencies CodeQL, Dependency Review ni JaCoCo.
5. No agregues secretos reales; usa variables de entorno y valores de prueba aislados.
6. Separa API, servicio, repositorio y seguridad en cambios revisables.
7. Meta de cobertura del código modificado: 85% o superior.

## Clean code

8. Cada método hace una sola cosa; si valida, accede a datos y arma la
   respuesta a la vez, sepáralo en capas.
9. Nombres que expliquen el propósito, no el tipo.
10. Sin duplicación: un bloque repetido se extrae a un método reutilizable.
11. Evitar anidamiento profundo; usar guard clauses / retorno anticipado.
12. Sin números o strings "mágicos" sueltos; usar constantes con nombre.