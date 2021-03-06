## Ejemplo simple de CRUD con Vue 2, Laravel 5.4 y Axios
Este codigo es un ejemplo de Crud con Vue 2 y Laravel 5.4 creado para apoyar los posts en [Laraveles](http://www.laraveles.com)

## Proyecto
Se ha creado un proyecto exclusivo para que sea una idea limpia y facil de cambiar.
La idea consiste en dar de alta empleados y asignarles un departamento y un cargo.

## Instalacion
Ir al terminal e ingresar a la carpeta raiz de su localhost

- git clone https://github.com/Gonzalo2310/CrudVue.git
- cd CrudVue
- renombrar .env.example como .env
- configurar .env con las credenciales de la base de datos
- composer install
- php artisan migrate
- npm i (si prefiere puede usar **yarn**)
- npm run dev (o **npm run prod** si fuera para produccion)
- aplicar permisos a carpetas (en linux y mac en el terminal en la carpeta del proyecto escribir: **chmod -R 777 public storage bootstrap/cache**)
- generar key unica (en el terminal escribir **php artisan key:generate**)
- escribir _http://localhost/CrudVue_ en su navegador


## Objetivo
- Crear CRUD simple. Departamento solo es un campo de texto
- Crear CRUD de modelos relacionados. Cargo es solo un campo de texto pero solo puede existir dentro de un departamento
- Crear CRUD de modelo complejo
- Validaciones simples en el front.
- Validaciones en el back y mensaje de error en el front
- Uso de componente externo Vue para calendario de campo fecha de nacimiento del empleado
- Creacion de atributos en modelos y uso
- Select relacionados

## Tecnologia Empleada.
- Laravel 5.4
- Vue 2 (2.3.4) 
- Bulma css
- DataPicker Vue-Picker
- Axios

## Informacion Ampliada

El material usado y el codigo esta explicado en una serie de post en [laraveles](http://www.laraveles.com/)

## License

Todo el codigo aqui expuesto es de libre uso sin restricciones.
