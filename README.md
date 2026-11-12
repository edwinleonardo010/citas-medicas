# citas-medicas

Taller de pruebas de software en Spring Boot (Java 25, Spring Boot 4.0.0, Maven).

- Aplicación: ejecutar `CitasApplication` y abrir http://localhost:8080/citas.html
- Pruebas: `mvn test` (excluye las etiquetadas `ui`)
- Cobertura: `mvn verify` y abrir `target/site/jacoco/index.html`
- Selenium: ejecutar `ReservaUITest` individualmente desde IntelliJ (requiere Google Chrome)
