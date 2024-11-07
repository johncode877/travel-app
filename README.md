
1. Iniciar proyecto npm: 

npm init

2. Instalar Tailwind como un plugin de PostCSS: 
npm install -D tailwindcss postcss autoprefixer

3. Crear las carpetas 
src/css/tailwind.css
public/css/tailwind.css

src/index.html

4. Incluir las directivas a src/css/tailwind.css:

@tailwind base;
@tailwind components;
@tailwind utilities;


5. Se ejecuta el siguiente comando, para crear el archivo de plantillas tailwind.config.js 
   colocando la siguiente configuración:
 
 npx tailwindcss init 
 
   

6. Para correr los estilos de Tailwind 
   ejecutar el siguiente comando 
   donde estamos indicando que nuestro archivo tailwind.css que proviene de src haga un build en la carpeta de public al archivo tailwind.css.
     
npx tailwindcss -i ./src/css/tailwind.css -o ./public/css/tailwind.css --watch 


## playground para practicar la sintaxis taiilwind

play.tailwindcss.com


## Plugins : Forms , Tipografia , Aspect-Ratio
npm install @tailwindcss/forms
npm install -D @tailwindcss/typography
npm install @tailwindcss/aspect-ratio

