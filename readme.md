# openapi-generator Konfiguration

- Verwende das `openapi-generator-maven-plugin`
- goals: `generate`
- spezifiziere den Pfad zur openapi-Datei mittels `inputSpec`
- verwende den Generator `spring` und die `spring-boot`-library
- spezifiziere das `apiPackage` mit `com.randstaddigital.workshop.api`
- spezifiziere das `modelPackage` mit `com.randstaddigital.workshop.dto`
- setze den `modelNameSuffix` auf `Dto`
- limitiere die `supportingFilesToGenerate` auf `ApiUtil.java`
- setze die `configOptions`:
  - `sourceFolder` auf `src/gen/java/main
  - `useSpringBoot3`
  - aktiviere `delegatePattern`

# Nützliche Informationen

Zugriff auf die Datenbank: http://localhost:8080/h2-console