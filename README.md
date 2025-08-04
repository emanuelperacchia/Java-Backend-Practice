# Estructura de Carpetas del Proyecto

```bash
├── 01-lambdas-streams/
│   ├── README.md
│   ├── src/
│   └── ejercicios.md
├── 02-sql-jpql-jpa/
│   ├── README.md
│   └── resources/
├── 03-rest-junit-mockito/
│   ├── README.md
│   └── ejercicios.md
├── 04-security-jwt/
│   ├── README.md
│   └── resources/
├── 05-ci-cd-actions/
│   ├── .github/workflows/ci.yml
│   ├── README.md
│   └── deploy-notes.md
└── 06-aws-deploy/
    ├── README.md
    └── scripts/
        ├── deploy.sh
        └── setup-ec2.md
```

# 🚀 Java Backend Bootcamp - Cronograma de 6 Semanas

¡Bienvenidos al Bootcamp de Backend Java! Soy tu instructor y te guiaré durante estas 6 semanas intensivas. Trabajaremos 2 horas diarias (6 días/semana) con el siguiente plan:

## 📚 Estructura del Repositorio
- [Repositorio Completo](.)
- [README General](../README.md)

---

## 🧪 Semana 1: Java Funcional - Lambdas y Streams
[Ver ejercicios](01-lambdas-streams/ejercicios.md) | [Teoría](01-lambdas-streams/README.md)

### 🎯 Objetivos:
- Dominar expresiones lambda e interfaces funcionales
- Implementar operaciones con Stream API

### 🧭 Desarrollo del Instructor:
"Hoy exploraremos el poder de la programación funcional en Java. Comenzaremos con una analogía: imaginen que las lambdas son como atajos para acciones comunes. Vamos a transformar bucles tradicionales en operaciones concisas con streams. ¿Listos para el reto del día? Implementaremos un filtrado de productos usando Predicate y luego haremos transformaciones con map."

### 🔗 Recursos:
- [Teoría Lambdas](https://certidevs.com/certificado-java-programacion-funcional)
- [Ejercicios Prácticos](https://certidevs.com/ejercicios-java-programacion-funcional)
- [Repositorio de Ejemplos](https://github.com/acelopezco/lambdas-lab)

---

## 🧑‍💻 Semana 2: SQL Avanzado y JPQL
[Ver ejercicios](02-sql-jpql-jpa/README.md)

### 🎯 Objetivos:
- Dominar JOINs, GROUP BY y subconsultas SQL
- Implementar consultas JPQL con Spring Data JPA

### 🧭 Desarrollo del Instructor:
"En nuestro segundo encuentro, conectaremos Java con bases de datos. Primero resolveremos un caso práctico: ¿Cómo obtener órdenes de clientes con sus detalles? Luego implementaremos la solución en JPQL usando @Query. Atención especial a la diferencia entre consultas SQL y JPQL - ¡no es lo mismo que parece!"

### 🔗 Recursos:
- [Ejercicios SQL/JPQL](https://certidevs.com/ejercicios-java-funciones-lambda-multirespuesta)
- [Tutorial JPQL](https://certidevs.com/tutorial-java-spring)
- [Repositorio Spring JPA](https://github.com/certidevs/spring)

---

## 🔬 Semana 3: REST APIs y Testing
[Ver ejercicios](03-rest-junit-mockito/ejercicios.md) | [Teoría](03-rest-junit-mockito/README.md)

### 🎯 Objetivos:
- Crear APIs REST con Spring Boot
- Implementar pruebas con JUnit 5 y Mockito

### 🧭 Desarrollo del Instructor:
"¡Manos al código! Hoy construiremos nuestro primer endpoint REST. Les mostraré cómo crear un CRUD completo en 30 minutos. Luego viene lo más importante: cómo probar nuestro código. Implementaremos tests con Mockito para simular dependencias externas. ¿Por qué es crucial? ¡Porque un código sin pruebas es como un barco sin salvavidas!"

### 🔗 Recursos:
- [Repositorio Spring Boot](https://github.com/certidevs/spring)
- [Curso Spring Boot](https://certidevs.com/curso-spring-boot)
- [Tutorial Testing](https://certidevs.com/certificado-spring-boot-api-rest)

---

## 🛡️ Semana 4: Seguridad con JWT
[Teoría](04-security-jwt/README.md)

### 🎯 Objetivos:
- Implementar autenticación JWT
- Proteger endpoints con Spring Security

### 🧭 Desarrollo del Instructor:
"Seguridad no es un lujo, es una necesidad. Hoy implementaremos un sistema completo de autenticación. Primero entenderemos el flujo JWT: desde el login hasta la protección de rutas. Luego configuraremos filtros y generaremos tokens. ¡Alerta importante! Nunca almacenen datos sensibles en los tokens."

### 🔗 Recursos:
- [Video Tutorial JWT](https://youtu.be/735a83FQR2I)
- [Tutorial Spring Security](https://certidevs.com/certificado-spring-boot-api-rest)
- [Repositorio Seguridad](https://github.com/certidevs/spring)

---

## 🧠 Semana 5: CI/CD con GitHub Actions
[Workflow CI](05-ci-cd-actions/.github/workflows/ci.yml) | [Notas](05-ci-cd-actions/deploy-notes.md) | [Teoría](05-ci-cd-actions/README.md)

### 🎯 Objetivos:
- Automatizar pruebas y builds
- Implementar pipelines CI/CD

### 🧭 Desarrollo del Instructor:
"Automatización es la clave para desarrollo profesional. Hoy crearemos nuestro primer pipeline que se activará con cada push. Configuraremos: 1) Ejecución de pruebas unitarias 2) Build del proyecto 3) Análisis de código. ¡Verán cómo esta inversión ahorra horas de trabajo manual!"

### 🔗 Recursos:
- [Tutorial GitHub Actions](https://github.com/certidevs/spring)
- [Ejemplo CI/CD](https://github.com/certidevs/spring)

---

## 🌐 Semana 6: Despliegue en AWS
[Script Despliegue](06-aws-deploy/scripts/deploy.sh) | [Guía EC2](06-aws-deploy/scripts/setup-ec2.md) | [Teoría](06-aws-deploy/README.md)

### 🎯 Objetivos:
- Desplegar aplicaciones en AWS EC2
- Configurar ambiente de producción

### 🧭 Desarrollo del Instructor:
"Último sprint: llevaremos nuestra aplicación a producción. Usaremos AWS con capa gratuita para no incurrir en costos. Aprenderán a: 1) Configurar instancias EC2 2) Abrir puertos de seguridad 3) Implementar actualizaciones sin downtime. ¡El momento más emocionante cuando vean su API en vivo!"

### 🔗 Recursos:
- [Video Tutorial AWS EC2](https://certidevs.com/certificado-spring-boot-api-rest)
- [Guía EC2 + MySQL](https://github.com/certidevs/spring)

---

## ✅ Recomendaciones Finales del Instructor
1. **Consistencia > Intensidad**: Mejor 2 horas diarias que 10 horas un solo día
2. **Código todos los días**: Aunque sean pequeños cambios, mantengan el repositorio activo
3. **Experimenten**: Modifiquen los ejemplos, rómpanlos y arréglenlos
4. **Documenten**: Comenten su código como si alguien más lo fuera a mantener
5. **Pregunten**: No pasen más de 30 minutos bloqueados sin pedir ayuda

"Este viaje transformará su forma de desarrollar aplicaciones backend. ¡Manos a la obra y nos vemos en el primer commit!" 🚀💻
