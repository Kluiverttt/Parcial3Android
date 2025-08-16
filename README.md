# Parcial3Android
Pasos para transformar una aplicacion de IONIC a Android 
Hay que seguir una serie de comandos para conseguir el objetivo. 
1. Primero debemos instalar las dependencias.
2. Agregar la plataforma Andorid.
ionic capacitor add android
3. Compilar la app, este comando generara los archivos web necesarios. 
ionic build
4. Sincronizar con Capacitor, esto copia los archivos compilados al proyecto
npx cap sync android
5. Abrir en Android Studio, este comando abrira el proyecto Andorid generado.
npx cap open android
Por ultimo en android studio podremos configurar el emulador o dispositivo fisico.
Ejecutamos con el boton "Run"
