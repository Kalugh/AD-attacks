# Creando usuarios en un AD

Dentro de nuestro windows server, abrimos el ```Administrador del servidor```

![164f8a322375511e30dd98be6148ba65](https://user-images.githubusercontent.com/107114264/173865506-253fa80c-7085-407d-95f9-fc7bec1a4331.png)

Nos iremos a ```Herramientas``` y dentro de este apartado a: ```Usuarios y equipos de Active Directory```

![c889c234d935335386dbb9034fdb994e](https://user-images.githubusercontent.com/107114264/173865671-7cfe710c-869a-4457-8454-b997e67abe0a.png)

Tendremos que entrar al apartado ```Users``` y aquí procederemos a cear dos nuevos usuarios.

![ca84bfd054b25c3f7a9a5a951dc731e8](https://user-images.githubusercontent.com/107114264/173866130-f4ae7275-9114-4995-83d4-374002d459c3.png)

Usando el click derecho, podemos darle a nuevo, aquí dentro elegir ```Usuario```

![735cac690af40985df1b5bab6b9df69c](https://user-images.githubusercontent.com/107114264/173866439-87225932-02f4-44a2-9e6e-fdcc19fb1079.png)

Crearemos dos usuarios con el nombre que eligáis, recomendando que eligáis el apartado de que la contraseña nunca expira.

![33aa2104fc562c71a92830af80e932b1](https://user-images.githubusercontent.com/107114264/173866862-f2ad5b13-1100-4bbc-b6b7-5e63c132a91a.png)

Eligiendo sólo un usuario para ver la comparativa, le daremos doble click, y entramos a ```Cuenta```

En ```Opciones de cuenta``` bajamos hasta ver:

![df10a2403747579f7748ea7e745d03a5](https://user-images.githubusercontent.com/107114264/173868081-46936027-e970-4714-93d0-c80f366984a4.png)

Seleccionamos la última opción, llamada ```No pedir la autentificación Kerberos previa```

Ya tenemos todo listo para ejecutar impacket y ver los tickets TGT(Ticket Granting Ticket).

# Obteniendo impacket
