# Primer-trabajo
Repositorio para taller de git y github de IAW

Se añade una nueva línea.

Se añade otra nueva línea.

# Encabezado de tipo h1

## Encabezado tipo h2

### Encabezado tipo h3

bla bla bla

**TEXTO EN NEGRITA**

__Texto en negrita__

*Texto en cursiva*

_texto en cursiva_

#   INSTTALACION DEL SERVIDOR WEB APACHE

Para instalar el servidor ejecutamos el comando `apt uptade && apt install apache2`.

Ejecutamos los siguientes comandos.

```
apt uptade
apt install apache2
```
crea el siguiente scirpt:

```bash
#!/bin/bash
echo "Hola mundo"
```

```python
celsius = float(input('Introduce una temperatura en grados Celsius: '))
farenheit = (1.8 * celsius) + 32
print(f'La temperatura en grados Farenheit es: {farenheit}')
```

```yaml
version: '3'

services: 
  apache:
    build: ./apache
    ports: 
      - 80:80
    volumes:
      - ./src:/var/www/html
```

[Web del Celia](https://iescelia.org/web/)

# Enlaces entre documentos internos
[Ir al archivo nuevo_archivo.md](nuevo_archivo.md)


[Ir al archivo ciber.md](seguridad/ciber.md)

Enlaces a la página web del [IES Celia Viñas][1] y a [GitHub][2].

Enlace a [texto](web)

[web]: https://google.es

[1]: https://iescelia.org
[2]: https://github.com

# Imagenes

![Texto alternativo](https://img.magnific.com/free-photo/closeup-shot-beautiful-butterfly-with-interesting-textures-orange-petaled-flower_181624-7640.jpg?semt=ais_hybrid&w=740&q=80)

# Imagenes internas

![](screenshots/imagen1.jpeg)

![](screenshots/imagen2.jpg)

![](screenshots/imagen3.jpg)

# Listas desordenadaas 

* Elemento 1
* Elemento 2
* Elemento 3

- Elemento 1
- Elemento 2
- Elemento 3


- Elemento 1
  - Elemento 1.1
  - Elemento 1.2
  - Elemento 1.3

- Elemento 2
    - Elemento 2.1
    - Elemento 2.2

Escribo una línea.  
Escribo otra línea.

Una línea.

Otra línea.


<!- Este texto es un comentario y no será renderizado -->


