# Hola, soy Angie Alvarez 👋  
**QA Engineer Jr | Manual & API Testing | Web & Mobile QA**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-angiedalvarez-blue?logo=linkedin)](https://www.linkedin.com/in/angiedalvarez/)
[![GitHub](https://img.shields.io/badge/GitHub-angiedalvarez-000?logo=github)](https://github.com/angiedalvarez)
[![Email](https://img.shields.io/badge/Email-Contactar-red)](mailto:angieaus28@gmail.com)

---

### Sobre mí
QA Engineer Jr bilingüe formada en **TripleTen**, enfocada en **pruebas manuales web y móviles** y en **validación de APIs REST**.  
Convierto requisitos en **casos de prueba reproducibles**, ejecuto **smoke/regresión** y documento defectos en **Jira** con pasos y evidencias claras. Manejo **Postman, SQL, Selenium WebDriver (Python básico), Android Studio y Chrome DevTools**.  
Me caracterizo por un enfoque **meticuloso y orientado a los detalles**, buscando la entrega de productos de **alta calidad** que mejoren la experiencia del usuario.

---

### Tecnologías y herramientas
- **Testing:** Casos de prueba, checklists, regresión, smoke, exploratorio, boundary/value, equivalencia  
- **APIs:** Postman (colecciones, variables, tests), REST, JSON  
- **Automatización (básica):** Python + Selenium WebDriver, PyCharm, `pytest`  
- **Móvil:** Android Studio (emulador), testing de notificaciones, permisos, offline  
- **Datos:** SQL (consultas de verificación)  
- **Dev & Colaboración:** Git/GitHub, Jira, Figma, Chrome DevTools, Cygwin

---

## Proyectos del bootcamp (públicos)

### 1) Urban Routes – Web App  🔗  
Repositorio: **https://github.com/angiedalvarez/qa-project-Urban-Routes-es**  
**Tipo:** QA Manual Web  
**Rol/Stack:** Casos de prueba, regresión, DevTools, SQL, Jira  
**Qué hice:**
- Diseñé **plan de pruebas** y **checklists** por módulos (búsqueda, rutas, costos).
- Apliqué **partición de equivalencia** y **valores límite**.
- Reporté bugs en **Jira** con pasos, resultado esperado/actual y evidencias.
- Realicé verificaciones puntuales de datos con **SQL**.

---

### 2) Urban Grocers – Mobile App (Android)  🔗  
Repositorio: **https://github.com/angiedalvarez/qa-project-Urban-Grocers-app-es**  
**Tipo:** QA Manual Mobile  
**Rol/Stack:** Android Studio (emulador), pruebas de **notificaciones**, permisos, flujos E2E  
**Qué hice:**
- Probé **escenarios críticos** (inicio de sesión, carrito, checkout).
- Verifiqué **notificaciones push** (background, lock screen, app en uso).
- Aseguré comportamiento con **conectividad** (sin red / reconexión).
- Documenté **incidencias** con capturas y pasos reproducibles.

---

### 3) API Stand Tests – Suite de pruebas a APIs  🔗  
Repositorio: **https://github.com/angiedalvarez/api_stand_tests**  
**Tipo:** Testing de API + Automatización básica  
**Stack:** **Python**, `pytest`, `requests`, **Postman**  
**Qué hice:**
- Escribí **tests positivos y negativos** para endpoints REST (creación, lectura, validaciones).
- Organicé pruebas por **módulos** y **fixtures** simples.
- Incluí instrucciones para ejecutar la suite y validar respuestas.

#### Cómo ejecutar (ejemplo)
```bash
# Clonar
git clone https://github.com/angiedalvarez/api_stand_tests.git
cd api_stand_tests

# Crear entorno (opcional) e instalar dependencias
python -m venv venv
source venv/bin/activate   # en Windows: venv\Scripts\activate
pip install -r requirements.txt

# Ejecutar suite
pytest -v

