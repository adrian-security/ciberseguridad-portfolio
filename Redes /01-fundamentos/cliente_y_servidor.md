# Cliente y servidor

[![Cliente](https://i.postimg.cc/Jzs7cXQF/Cliente.jpg)](https://postimg.cc/pmttPp4Q)

## 1. ¿Qué es un cliente?
Un cliente es un dispositivo o programa que solicita información o servicios a otros dispositivos o programas.

**Por ejemplo**:
* El ordenador cuando navegas por Internet.
* El móvil cuando utilizas Instagram.
* El navegador cuando visitas una página web.
* Una aplicación cuando consulta información de una base de datos.

**Ejemplo**: abres el Google Chrome y escribes www.google.com.
El navegador actúa como cliente porque está solicitando información a un servidor. 

## 2. ¿Qué es un servidor?
Un servidor es un equipo o programa que proporciona información, recursos o servicios a otros dispositivos o programas.

Algunos ejemplos:

| Tipo de servidor | Función |
| :--- | :--- |
| **Servidor web** | Aloja páginas web. |
| **Servidor de correo** | Gestiona el correo electrónico. |
| **Servidor de archivos** | Almacena y comparte archivos. |
| **Servidor DNS** | Traduce nombres de dominio a direcciones IP. |
| **Servidor de bases de datos** | Almacena y proporciona datos. |
| **Servidor de autenticación** | Gestiona la identificación de usuarios. |

> 🔒 **Una cosa importante:** un servidor no tiene por qué ser un ordenador enorme en un centro de datos. Puede ser un ordenador normal ejecutando un programa que ofrece servicios a otros equipos.

## 3. ¿Cómo se comunican un cliente y un servidor?
Vamos a responder a partir de un ejemplo que hacemos todos los días: visitar una página web.

Imagina que queremos acceder a Amazon desde el navegador:

www.amazon.es

¿Qué sucede?

[![Cliente-servidor.jpg](https://i.postimg.cc/9fdgwxsR/Cliente-servidor.jpg)](https://postimg.cc/QBMJRq8h)

### Paso 1. El cliente realiza una solicitud.

Tu navegador solicita acceder a la página web.

### Paso 2. Se localiza el servidor.

Se utiliza DNS para encontrar la dirección IP asociada al dominio.

### Paso 3. Se establece la comunicación. 

Tu ordenador se comunica con el servidor utilizando los protocolos correspondientes. Por ejemplo, TCP y TLS en una conexión HTTPS tradicional.

### Paso 4. El servidor procesa la solicitud.

El servidor recibe la petición y prepara la respuesta.

### Paso 4. El servidor procesa la solicitud.

El servidor recibe la petición y prepara la respuesta.

### Paso 5. El servidor responde.

Envía los datos solicitados al cliente.

### Paso 6. El navegador muestra la página.

Tu navegador interpreta la información recibida y muestra el contenido.


> 🔒 **Conceptos clave:**
> 
> * **`Cliente`** — Solicita información.
> * **`Servidor`** — Proporciona información.
> * **`Solicitud`** — Petición del cliente.
> * **`Respuesta`** — Información que devuelve el servidor.


## 4. ¿Qué es el modelo cliente-servidor?
Es una arquitectura de comunicación en la que los clientes solicitan servicios y los servidores los proporcionan.

Por ejemplo, una empresa puede tener:
* 50 ordenadores de trabajadores.
* Un servidor de archivos.
* Un servidor de correo.
* Un servidor de autenticación.
* Un servidor web.

Los trabajadores utilizan sus ordenadores para solicitar información a esos servidores.

[![Modelo-Cliente-servidor.jpg](https://i.postimg.cc/KzqXpGxx/Modelo-Cliente-servidor.jpg)](https://postimg.cc/jw7kLrDF)



