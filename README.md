# Automatización Web en Swag Labs con Katalon Studio

## Descripción

Proyecto de pruebas automatizadas web construido con **Katalon Studio** sobre **Swag Labs** (`Page_Swag Labs`), con casos de prueba independientes y ejecución agrupada mediante Test Suite.

## Tecnologías y Herramientas

- **Framework de Automatización:** Katalon Studio
- **Tipo de Pruebas:** Automatización Web (UI)
- **Aplicación bajo Prueba:** Swag Labs

## Cobertura de Pruebas y Buenas Prácticas

- **Casos de prueba (Test Cases):** `TestLogin` y `TestLoginBloqueado`.
- **Suite de pruebas (Test Suites):** `TS_LoginDataDriven` agrupando los casos de prueba.
- **Objetos (`Object Repository/Page_Swag Labs`):** campos de usuario y contraseña, botón de login, agregar producto al carrito (*Sauce Labs Backpack*), checkout e información de compra.

## Ejemplo de Caso de Prueba

**Escenario:** Inicio de sesión válido en Swag Labs (`TestLogin`).

1. Abrir el navegador y navegar a la aplicación web Swag Labs.
2. Ingresar el usuario y la contraseña en los campos correspondientes del `Object Repository` (`Page_Swag Labs`).
3. Hacer clic en el botón de inicio de sesión (`input_login-button`).
4. **Resultado esperado:** El acceso se realiza correctamente y se habilita la navegación al inventario / carrito.

## Evidencia de Ejecución

<img width="1917" height="961" alt="Captura de pantalla 2026-11-25 161636" src="https://github.com/user-attachments/assets/6ff8cd0b-3706-4a82-831b-4e98e6a630e4" />


## Cómo Ejecutar el Proyecto

1. Abra el proyecto (`MiPrimerProyectoWeb`) en Katalon Studio.
2. Ejecute un caso de prueba desde **Test Cases** o corra la suite `TS_LoginDataDriven` desde **Test Suites**.
3. Revise los resultados en la consola, el visor de logs (`Log Viewer`) o la pestaña `Result` de Katalon.

## Autor

- **Flavio Matías Baldini** – QA Automation Tester
- **LinkedIn:** 
