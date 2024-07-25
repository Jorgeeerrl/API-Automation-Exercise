<img align="left" src="https://github.com/Jorgeeerrl/API-Automation-Exercise/blob/main/recursos/logoautomationexercise.png" width="450" />
<br clear="left"/>

# Proyecto de Automatización de APIs
Este proyecto tiene como objetivo automatizar la interacción con las APIs de un sitio web utilizando una colección de Postman. La automatización permite realizar pruebas y validar el correcto funcionamiento de las APIs, asegurando que los servicios web funcionen según lo esperado.

## Características del Proyecto
- **Ejecución Automática de Pruebas:** Todas las pruebas de las APIs se ejecutan de forma automatizada mediante la integración de Postman con Newman, lo que permite la validación continua del sistema sin intervención manual.
- **Validaciones Exhaustivas:** Se verifican las respuestas de las APIs para asegurar que contengan los datos esperados y que los códigos de estado sean correctos. Esto incluye la validación de esquemas JSON y la verificación de valores específicos en las respuestas.
- **Manejo de Variables Dinámicas:** Se utilizan variables para gestionar datos dinámicos como nombres de usuarios, productos, etc., facilitando la reutilización y la flexibilidad en las pruebas.
- **Diversidad de Escenarios de Prueba:** Se incluyen scripts de prueba predefinidos que validan múltiples escenarios de uso, abarcando tanto casos con datos válidos como inválidos. Esto asegura una cobertura amplia y detallada de las posibles interacciones con las APIs.
- **Informes Detallados:** Generación de informes detallados sobre los resultados de las pruebas, incluyendo estadísticas de éxito/fallo y detalles de cada petición y respuesta, lo cual facilita el análisis y la resolución de problemas.
- **Integración Continua:** Compatible con sistemas de integración continua (CI) como Jenkins, permitiendo la ejecución automática de pruebas en cada ciclo de desarrollo y asegurando la calidad del software en cada etapa.


<div>
  <div style="display: inline-block;">
    <img align="left" src="https://github.com/Jorgeeerrl/API-Automation-Exercise/blob/main/recursos/API11%20-%20Body.jpg" height="175" />
    <img align="left" src="https://github.com/Jorgeeerrl/API-Automation-Exercise/blob/main/recursos/API11%20-%20Pre-req.jpg" height="175" />
    <img align="left" src="https://github.com/Jorgeeerrl/API-Automation-Exercise/blob/main/recursos/API5%20-%20Post-req.jpg" height="175" />
</div>
<br clear="left"/>

## APIs Automatizadas
A continuación, se detalla la lista de las APIs que han sido automatizadas en este proyecto:

<details>
  <summary><strong>✅API 1: Get All Products List</strong></summary>
&nbsp;

<ul>                          
    <li class="list item"><strong>API URL:</strong> https://automationexercise.com/api/productsList</li>         
    <li class="list item"><strong>Request Method:</strong> GET</li>         
    <li class="list item"><strong>Response Code:</strong> 200</li>       
    <li class="list item"><strong>Response JSON:</strong> All products list</li>
</ul>
<img align="left" src="https://github.com/Jorgeeerrl/API-Automation-Exercise/blob/main/recursos/API1%20-%20Post-req.jpg" width="450" />
<br clear="left"/>
&nbsp;
</details>

<details>
  <summary><strong>✅API 2: POST To All Products List</strong></summary>
&nbsp;

<ul>                          
    <li class="list item"><strong>API URL:</strong> https://automationexercise.com/api/productsList</li>         
    <li class="list item"><strong>Request Method:</strong> POST</li>         
    <li class="list item"><strong>Response Code:</strong> 405</li>       
    <li class="list item"><strong>Response Message:</strong> This request method is not supported.</li>
</ul>
<img align="left" src="https://github.com/Jorgeeerrl/API-Automation-Exercise/blob/main/recursos/API2%20-%20Post-req.jpg" width="450" />
<br clear="left"/>
&nbsp;
</details>

<details>
  <summary><strong>✅API 3: Get All Brands List</strong></summary>
&nbsp;

<ul>                          
    <li class="list item"><strong>API URL:</strong> https://automationexercise.com/api/brandsList</li>         
    <li class="list item"><strong>Request Method:</strong> GET</li>         
    <li class="list item"><strong>Response Code:</strong> 200</li>       
    <li class="list item"><strong>Response JSON:</strong> All brands list</li>
</ul>
<img align="left" src="https://github.com/Jorgeeerrl/API-Automation-Exercise/blob/main/recursos/API3%20-%20Post-req.jpg" width="450" />
<br clear="left"/>
&nbsp;
</details>

<details>
  <summary><strong>✅API 4: PUT To All Brands List</strong></summary>
&nbsp;

<ul>                          
    <li class="list item"><strong>API URL:</strong> https://automationexercise.com/api/brandsList</li>         
    <li class="list item"><strong>Request Method:</strong> PUT</li>         
    <li class="list item"><strong>Response Code:</strong> 405</li>       
    <li class="list item"><strong>Response Message:</strong> This request method is not supported.</li>
</ul>
<img align="left" src="https://github.com/Jorgeeerrl/API-Automation-Exercise/blob/main/recursos/API4%20-%20Post-req.jpg" width="450" />
<br clear="left"/>
&nbsp;
</details>

<details>
  <summary><strong>✅API 5: POST To Search Product</strong></summary>
&nbsp;

<ul>                          
    <li class="list item"><strong>API URL:</strong> https://automationexercise.com/api/searchProduct</li>         
    <li class="list item"><strong>Request Method:</strong> POST</li> 
    <li class="list item"><strong>Request Parameter:</strong> search_product (For example: top, tshirt, jean)</li>        
    <li class="list item"><strong>Response Code:</strong> 200</li>       
    <li class="list item"><strong>Response JSON:</strong> Searched products list</li>
</ul>
<div>
  <img align="left" src="https://github.com/Jorgeeerrl/API-Automation-Exercise/blob/main/recursos/API5%20-%20Pre-req.jpg" height="200" />
  <img align="left" src="https://github.com/Jorgeeerrl/API-Automation-Exercise/blob/main/recursos/API5%20-%20Post-req.jpg" height="200" />
</div>
<br clear="left"/>
&nbsp;
</details>

<details>
  <summary><strong>✅API 6: POST To Search Product without search_product parameter</strong></summary>
&nbsp;

<ul>                          
    <li class="list item"><strong>API URL:</strong> https://automationexercise.com/api/searchProduct</li>         
    <li class="list item"><strong>Request Method:</strong> POST</li>         
    <li class="list item"><strong>Response Code:</strong> 400</li>       
    <li class="list item"><strong>Response Message:</strong> Bad request, search_product parameter is missing in POST request.</li>
</ul>
<img align="left" src="https://github.com/Jorgeeerrl/API-Automation-Exercise/blob/main/recursos/API6%20-%20Post-req.jpg" width="450" />
<br clear="left"/>
&nbsp;
</details>

<details>
  <summary><strong>✅API 7: POST To Verify Login with valid details</strong></summary>
&nbsp;

<ul>                          
    <li class="list item"><strong>API URL:</strong> https://automationexercise.com/api/verifyLogin</li>         
    <li class="list item"><strong>Request Method:</strong> POST</li>         
    <li class="list item"><strong>Request Parameters:</strong> email, password</li>       
    <li class="list item"><strong>Response Code:</strong> 200</li>       
    <li class="list item"><strong>Response Message:</strong> User exists!</li>
</ul>
<div>
  <img align="left" src="https://github.com/Jorgeeerrl/API-Automation-Exercise/blob/main/recursos/API7%20-%20Body.jpg" height="200" />
  <img align="left" src="https://github.com/Jorgeeerrl/API-Automation-Exercise/blob/main/recursos/API7%20-%20Post-req.jpg" height="200" />
</div>
<br clear="left"/>
&nbsp;
</details>

<details>
  <summary><strong>✅API 8: POST To Verify Login without email parameter</strong></summary>
&nbsp;

<ul>                          
    <li class="list item"><strong>API URL:</strong> https://automationexercise.com/api/verifyLogin</li>         
    <li class="list item"><strong>Request Method:</strong> POST</li>         
    <li class="list item"><strong>Request Parameter:</strong> password</li>       
    <li class="list item"><strong>Response Code:</strong> 400</li>       
    <li class="list item"><strong>Response Message:</strong> Bad request, email or password parameter is missing in POST request.</li>
</ul>
<img align="left" src="https://github.com/Jorgeeerrl/API-Automation-Exercise/blob/main/recursos/API8%20-%20Post-req.jpg" width="450" />
<br clear="left"/>
&nbsp;
</details>

<details>
  <summary><strong>✅API 9: DELETE To Verify Login</strong></summary>
&nbsp;

<ul>                          
    <li class="list item"><strong>API URL:</strong> https://automationexercise.com/api/verifyLogin</li>         
    <li class="list item"><strong>Request Method:</strong> DELETE</li>         
    <li class="list item"><strong>Response Code:</strong> 405</li>       
    <li class="list item"><strong>Response Message:</strong> This request method is not supported.</li>
</ul>
<img align="left" src="https://github.com/Jorgeeerrl/API-Automation-Exercise/blob/main/recursos/API9%20-%20Post-req.jpg" width="450" />
<br clear="left"/>
&nbsp;
</details>

<details>
  <summary><strong>✅API 10: POST To Verify Login with invalid details</strong></summary>
&nbsp;

<ul>                          
    <li class="list item"><strong>API URL:</strong> https://automationexercise.com/api/verifyLogin</li>         
    <li class="list item"><strong>Request Method:</strong> POST</li>         
    <li class="list item"><strong>Request Parameters:</strong> email, password (invalid values)</li>       
    <li class="list item"><strong>Response Code:</strong> 404</li>       
    <li class="list item"><strong>Response Message:</strong> User not found!</li>
</ul>
<img align="left" src="https://github.com/Jorgeeerrl/API-Automation-Exercise/blob/main/recursos/API10%20-%20Post-req.jpg" width="450" />
<br clear="left"/>
&nbsp;
</details>

<details>
  <summary><strong>✅API 11: POST To Create/Register User Account</strong></summary>
&nbsp;

<ul>                          
    <li class="list item"><strong>API URL:</strong> https://automationexercise.com/api/createAccount</li>         
    <li class="list item"><strong>Request Method:</strong> POST</li>         
    <li class="list item"><strong>Request Parameters:</strong> name, email, password, title (for example: Mr, Mrs, Miss), birth_date, birth_month, birth_year, firstname, lastname, company, address1, address2, country, zipcode, state, city, mobile_number</li>       
    <li class="list item"><strong>Response Code:</strong> 201</li>       
    <li class="list item"><strong>Response Message:</strong> User created!</li>
</ul>
<div>
  <img align="left" src="https://github.com/Jorgeeerrl/API-Automation-Exercise/blob/main/recursos/API11%20-%20Body.jpg" height="400" />
  <div style="display: inline-block;">
    <img align="top" src="https://github.com/Jorgeeerrl/API-Automation-Exercise/blob/main/recursos/API11%20-%20Pre-req.jpg" height="200" />
    <img align="bottom" src="https://github.com/Jorgeeerrl/API-Automation-Exercise/blob/main/recursos/API11%20-%20Post-req.jpg" height="200" />
  </div>
</div>
<br clear="left"/>
&nbsp;
</details>

<details>
  <summary><strong>✅API 12: DELETE METHOD To Delete User Account</strong></summary>
&nbsp;

<ul>                          
    <li class="list item"><strong>API URL:</strong> https://automationexercise.com/api/deleteAccount</li>         
    <li class="list item"><strong>Request Method:</strong> DELETE</li>         
    <li class="list item"><strong>Request Parameters:</strong> email, password</li>       
    <li class="list item"><strong>Response Code:</strong> 200</li>       
    <li class="list item"><strong>Response Message:</strong> Account deleted!</li>
</ul>
<img align="left" src="https://github.com/Jorgeeerrl/API-Automation-Exercise/blob/main/recursos/API12%20-%20Post-req.jpg" width="450" />
<br clear="left"/>
&nbsp;
</details>

<details>
  <summary><strong>✅API 13: PUT METHOD To Update User Account</strong></summary>
&nbsp;

<ul>                          
    <li class="list item"><strong>API URL:</strong> https://automationexercise.com/api/updateAccount</li>         
    <li class="list item"><strong>Request Method:</strong> PUT</li>         
    <li class="list item"><strong>Request Parameters:</strong> name, email, password, title (for example: Mr, Mrs, Miss), birth_date, birth_month, birth_year, firstname, lastname, company, address1, address2, country, zipcode, state, city, mobile_number</li>       
    <li class="list item"><strong>Response Code:</strong> 200</li>       
    <li class="list item"><strong>Response Message:</strong> User updated!</li>
</ul>
<div>
  <img align="left" src="https://github.com/Jorgeeerrl/API-Automation-Exercise/blob/main/recursos/API13%20-%20Body.jpg" height="350" />
  <div style="display: inline-block;">
    <img align="top" src="https://github.com/Jorgeeerrl/API-Automation-Exercise/blob/main/recursos/API13%20-%20Pre-req.jpg" height="175" />
    <img align="bottom" src="https://github.com/Jorgeeerrl/API-Automation-Exercise/blob/main/recursos/API13%20-%20Post-req.jpg" height="175" />
  </div>
</div>
<br clear="left"/>
&nbsp;
</details>

<details>
  <summary><strong>✅API 14: GET user account detail by email</strong></summary>
&nbsp;

<ul>                          
    <li class="list item"><strong>API URL:</strong> https://automationexercise.com/api/getUserDetailByEmail</li>         
    <li class="list item"><strong>Request Method:</strong> GET</li>         
    <li class="list item"><strong>Request Parameters:</strong> email</li>       
    <li class="list item"><strong>Response Code:</strong> 200</li>       
    <li class="list item"><strong>Response JSON:</strong> User Detail</li>
</ul>
<img align="left" src="https://github.com/Jorgeeerrl/API-Automation-Exercise/blob/main/recursos/API14%20-%20Post-req.jpg" width="450" />
<br clear="left"/>
&nbsp;
</details>


