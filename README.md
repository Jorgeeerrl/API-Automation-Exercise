# Proyecto de Automatización de APIs
Este proyecto tiene como objetivo automatizar la interacción con las APIs de un sitio web utilizando una colección de Postman. La automatización permite realizar pruebas y validar el correcto funcionamiento de las APIs, asegurando que los servicios web funcionen según lo esperado.

## Características del Proyecto
- **Automatización Completa:** Todas las pruebas de las APIs se ejecutan automáticamente, lo que facilita la validación continua del sistema.
- **Validaciones Detalladas:** Las respuestas de las APIs son verificadas para asegurar que contengan los datos esperados y que los códigos de estado sean correctos.
- **Variables Dinámicas:** Uso de variables para manejar datos dinámicos como nombres de usuarios, productos, etc.
- **Pruebas Predefinidas:** Scripts de prueba predefinidos que validan múltiples escenarios de uso, incluyendo casos con datos válidos e inválidos.

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
<img align="left" src="https://github.com/Jorgeeerrl/API-Automation-Exercise/blob/main/recursos/API5%20-%20Pre-req.jpg" width="450" />
<img align="left" src="https://github.com/Jorgeeerrl/API-Automation-Exercise/blob/main/recursos/API5%20-%20Post-req.jpg" width="450" />
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
<img align="left" src="https://github.com/Jorgeeerrl/API-Automation-Exercise/blob/main/recursos/API7%20-%20Body.jpg" width="450" />
<img align="left" src="https://github.com/Jorgeeerrl/API-Automation-Exercise/blob/main/recursos/API7%20-%20Post-req.jpg" width="450" />
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
<img align="left" src="https://github.com/Jorgeeerrl/API-Automation-Exercise/blob/main/recursos/API11%20-%20Body.jpg" width="450" />
<img align="left" src="https://github.com/Jorgeeerrl/API-Automation-Exercise/blob/main/recursos/API11%20-%20Pre-req.jpg" width="450" />
<img align="left" src="https://github.com/Jorgeeerrl/API-Automation-Exercise/blob/main/recursos/API11%20-%20Post-req.jpg" width="450" />
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
<img align="left" src="https://github.com/Jorgeeerrl/API-Automation-Exercise/blob/main/recursos/API13%20-%20Body.jpg" width="450" />
<img align="left" src="https://github.com/Jorgeeerrl/API-Automation-Exercise/blob/main/recursos/API13%20-%20Pre-req.jpg" width="450" />
<img align="left" src="https://github.com/Jorgeeerrl/API-Automation-Exercise/blob/main/recursos/API13%20-%20Post-req.jpg" width="450" />
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


