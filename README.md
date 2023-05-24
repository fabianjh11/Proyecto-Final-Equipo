# Proyecto Final Equipo
Proyecto FullStack de un E-Commerce utilizando Vue, Nuxt, Supabase, Stripe

## App Setup (localhost)

Se utilizó Vue 3, Nux 3
Demás herramientas y versiones específicas se encuentran en el archivo package.json
```
git clone https://github.com/fabianjh11/Proyecto-Final-Equipo.git

cp .env.example .env

npm install --legacy-peer-deps

npx prisma generate

npm run dev
```
Es necesario contar con una cuenta de Supabase y de Stripe, después añadir todos los detalles en el archivo .env

Ya que se conectó la aplicación a Supabase, se debe configurar la autenticación de Google
    https://cloud.google.com
    https://supabase.com/docs/guides/auth/social-login/auth-google

Ahora es necesario ejecutar el comando para migrar las tablas de la base de datos y correr el archivo seed

```
npx prisma migrate dev --name init
```

Ese sería todo el proceso

# Capturas

Página principal:
![54fcbd9d-57c2-4fda-a53f-36a4c5c8cb8a](https://github.com/fabianjh11/Proyecto-Final-Equipo/assets/105388163/3f3985ff-db6b-4eb4-94df-d2db979a97c8)

Es posible seleccionar un producto del catalogo.

![f22a505f-2493-40d0-b900-bf54be1b6f71](https://github.com/fabianjh11/Proyecto-Final-Equipo/assets/105388163/50bc091c-ff10-49e3-9095-a3c8e92f2b6f)


Puedes revisar el carrito de compras, si no tienes cuenta te solicita que inicies sesión.

![6057d84b-1e36-4ee6-95d6-ff53f815cb2e](https://github.com/fabianjh11/Proyecto-Final-Equipo/assets/105388163/437c61fc-21f3-4ecc-96a6-c9fafed437f6)


Inicias sesión con tu cuenta de Google.

![435f2a51-19a2-4624-acb7-4a8875088aa3](https://github.com/fabianjh11/Proyecto-Final-Equipo/assets/105388163/37f899f0-ab41-49e5-9414-2a756e2fd035)


Seleccionas un producto del catálogo y se muestra en el carrito.

![567ac512-1cc3-48a9-853e-c2722c87fb38](https://github.com/fabianjh11/Proyecto-Final-Equipo/assets/105388163/07b1ab53-4c61-493a-a2d6-6d9bb17b7d37)
![88368b3e-adcc-4ced-94a8-e9007de7b763](https://github.com/fabianjh11/Proyecto-Final-Equipo/assets/105388163/8117944d-f6ed-4340-b775-8b10ec45d3db)


Selecciona el artículo dentro del carrito y seguido das click al botón Checkout.

![b5a838e5-31d4-4def-b020-9943f0de9d01](https://github.com/fabianjh11/Proyecto-Final-Equipo/assets/105388163/4e8fc2b7-16d5-4687-bbc3-3c5e4f913424)


Ingresas tu dirección llenando el formulario.

![35ef2645-85fd-4c0f-9eb2-6fd3366a3aa7](https://github.com/fabianjh11/Proyecto-Final-Equipo/assets/105388163/f32620e1-5d55-4b25-999b-d72e258a5e85)


Ingresas los datos de la tarjeta con la que realizarás la compra, para prueba puedes utilizar la siguiente: 4242 4242 4242 4242  Vigencia 12/24  CVC: 123

![4f352e75-0e8d-43aa-9ebc-df2a25ddb5a8](https://github.com/fabianjh11/Proyecto-Final-Equipo/assets/105388163/cbd403f3-a44f-450d-b6ee-4e23fb12f165)
![761e86ee-9737-41d4-aa12-297f2aa96cc6](https://github.com/fabianjh11/Proyecto-Final-Equipo/assets/105388163/eacfde9b-a721-4c32-a7af-33e0d290cc90)


El pago se realiza y puedes consultar las ordenes realizadas.

![9a9c9028-cca7-4300-95cd-abb76c967892](https://github.com/fabianjh11/Proyecto-Final-Equipo/assets/105388163/d7586b13-34cc-4932-b75f-3c6e0ada1c4f)
