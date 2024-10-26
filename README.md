# Documentación del Taller de CI/CD
## Sebastian Velez Galeano.

## Enlaces Importantes

- 🔗 Repositorio del Proyecto: [svgprotobootapp](https://github.com/sebastianvelezg/svgprotobootapp)
- 🚀 URL de Despliegue: [Ambiente de Producción](protobootapp-env-prod-svg.eba-fiwp24jg.us-east-2.elasticbeanstalk.com)

## Pipeline Implementations

### 1. GitHub Actions CI Pipeline

#### Características Implementadas
- Compilación con Java 17
- Ejecución de pruebas unitarias con JUnit
- Pruebas de integración con Spring Boot Test
- Análisis estático con Checkstyle, PMD y SpotBugs
- Medición de cobertura de código con JaCoCo

#### Evidencias
  
<img width="1680" alt="Screenshot 2024-10-25 at 10 45 15 PM" src="https://github.com/user-attachments/assets/1fea9eca-472f-4e7d-a719-dc5fd52ab967">
<img width="1680" alt="Screenshot 2024-10-25 at 10 49 38 PM" src="https://github.com/user-attachments/assets/903ae1e2-83d5-4fc8-adb4-1663eb38130a">
<img width="1680" alt="Screenshot 2024-10-25 at 10 50 26 PM" src="https://github.com/user-attachments/assets/c3b0c581-3bc3-4101-9c3d-de9712f5891b">
<img width="1680" alt="Screenshot 2024-10-25 at 10 51 00 PM" src="https://github.com/user-attachments/assets/5d48153f-56af-46c5-92fc-bfd581cc04db">

### 2. Jenkins Local CI Pipeline

#### Características Implementadas
- Integración con GitHub para obtener el código fuente
- Configuración de build con Maven
- Ejecución automatizada de pruebas
- Publicación de reportes JUnit
- Análisis de código con herramientas estáticas
- Medición de cobertura con JaCoCo

#### Evidencias
  
<img width="1680" alt="Screenshot 2024-10-25 at 10 55 05 PM" src="https://github.com/user-attachments/assets/fc9d2519-f9ee-48c5-9e55-a0990319b14e">
<img width="1680" alt="Screenshot 2024-10-25 at 10 55 28 PM" src="https://github.com/user-attachments/assets/5d4d96ba-67f7-429c-95fe-48aede028424">
<img width="1680" alt="Screenshot 2024-10-25 at 10 55 46 PM" src="https://github.com/user-attachments/assets/84d8568d-7e5b-478b-82e7-c8cc073dc5b8">
<img width="1680" alt="Screenshot 2024-10-25 at 10 56 22 PM" src="https://github.com/user-attachments/assets/c703d57e-ce7e-4d1f-93a0-3983effd2ee4">
<img width="1680" alt="Screenshot 2024-10-25 at 10 57 34 PM" src="https://github.com/user-attachments/assets/ce58dc05-952c-4c3e-899f-837c91071710">
<img width="1680" alt="Screenshot 2024-10-25 at 10 57 49 PM" src="https://github.com/user-attachments/assets/f1aa02fd-d34d-4b59-a9e8-7d4eff85fcbc">
<img width="1679" alt="Screenshot 2024-10-25 at 10 58 07 PM" src="https://github.com/user-attachments/assets/6434bc56-74bc-4e03-86df-d9a7de2977b9">
<img width="1680" alt="Screenshot 2024-10-25 at 10 59 10 PM" src="https://github.com/user-attachments/assets/20543413-eb6f-4a9a-a91b-4112c108715b">
<img width="629" alt="Screenshot 2024-10-25 at 10 59 34 PM" src="https://github.com/user-attachments/assets/c747ffd9-c5fe-4f79-ac44-b389e6c8ab54">

### 3. AWS CI/CD Pipeline

#### Características Implementadas
- CodePipeline para la orquestación
- CodeBuild para la integración continua
- Elastic Beanstalk para el despliegue
- Configuración de dos ambientes (staging y producción)
- Aprobación manual entre ambientes
- Monitoreo con CloudWatch

#### Evidencias
  
![unnamed](https://github.com/user-attachments/assets/eefbe9b1-0af2-4c36-a2a5-efdd62402224)
![unnamed-2](https://github.com/user-attachments/assets/50ca879a-a52b-4df0-9e8c-7e9c7fa9e62d)
![unnamed-3](https://github.com/user-attachments/assets/ce1454bf-94d6-4190-a6fc-0b6e7feee589)
![unnamed-4](https://github.com/user-attachments/assets/c009ac15-4ae7-4458-9a9d-c0bc2a639336)
![unnamed-5](https://github.com/user-attachments/assets/e1b41923-86c7-40b3-9f42-1786622ccc53)
![unnamed-6](https://github.com/user-attachments/assets/57694812-514a-4ebb-afd9-bc99634cd4af)
![unnamed-7](https://github.com/user-attachments/assets/31a27aad-9c5c-410d-a1aa-21ca9ada9dd2)
![unnamed-8](https://github.com/user-attachments/assets/b756fc98-eaf4-4344-a205-86d32b80e3e7)
![unnamed-9](https://github.com/user-attachments/assets/c963c6ab-cc7e-4543-ad81-680aeff590e6)
![unnamed-10](https://github.com/user-attachments/assets/550c5032-d8d0-431c-ad7a-6bf6ac47dcf0)
![unnamed-11](https://github.com/user-attachments/assets/70769fb8-405d-477d-b0bf-419ca2545a31)
![unnamed-12](https://github.com/user-attachments/assets/f9f0d8a8-711f-417e-9018-1ebe7ea75930)
![unnamed-13](https://github.com/user-attachments/assets/4b385574-4acd-4aae-8242-b8c606b007b7)
![unnamed-14](https://github.com/user-attachments/assets/b1b6e855-3e94-44c2-9558-4702f5b9d90f)
![unnamed-15](https://github.com/user-attachments/assets/d59a17ac-071f-465b-b634-58214d83050b)
![unnamed-16](https://github.com/user-attachments/assets/5266ee16-4764-4338-9ac2-d0b211c5ef0b)

## Tecnologías Utilizadas

### Core
- Java 17
- Spring Boot
- Maven

### Testing & Quality
- JUnit
- Spring Boot Test
- JaCoCo
- Checkstyle
- PMD
- SpotBugs

### CI/CD Platforms
- GitHub Actions
- Jenkins
- AWS Suite
  - CodePipeline
  - CodeBuild
  - Elastic Beanstalk
  - CloudWatch



