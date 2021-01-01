# SpyBotDiscord
[ES]:Este bot de Discord envía los mensajes junto con otros datos a la terminal del sistema, también, puedes hacer que se envíen a un canal de texto, pero hacen falta una modificaciones por parte de quien lo vaya a usar. [EN]: This Discord bot sends the messages along with other data to the system terminal, also, you can have them sent to a text channel, but they require modifications by whoever is going to use it.

# Instrucciones [ES]:
1. Ve a la página de “Discord developers portal”:
https://discord.com/developers/applications
2. Haz click en “New Application”, introduce el nombre que quieras que tenga tu bot. (Podrás cambiarlo más adelante)
3. Una vez creada tu aplicación, podrás cambiar su foto de perfil, su nombre y su descripción, recuerda que no puedes compartir el “Client secret”
4. En “SETTINGS”, ve a la pestaña “Bot” y haz click en “Add Bot”, haz click en “Acept”, podrás cambiar la foto de perfil de tu bot, su nombre (recuerda que si tiene  un nombre muy utilizado, deberás cambiarlo) (recomendamos desmarcar donde dice “Public Bot” para que solo tu lo puedas invitar a los servidores) (Es MUY importante que no compartas el “TOKEN” de tu bot)
5. En “General information”, ve copia el “Client ID” de tu bot, ve a la página de “Discord permissions calculator”: (https://discordapi.com/permissions.html#68608) y marca los siguientes permisos:
- Read Message History
- Send Messages
- Read Messages
- View Channel
6. Pega el “Client ID” de tu bot donde dice: “Client ID:” y haz click en el enlace de abajo, simplemente, invita al bot a tu server como lo harías con cualquier otro.
7. Si estás en Windows, ejecuta el archivo “BOT.bat” o “BOT” como administrador, saldrá una terminal de Windows donde se enviarán los mensajes junto con los datos. Si estás en linux o en MacOS, guarda la carpeta que has descargado en el escritorio, abre la terminal del sistema y escribe el siguiente comando: “CD DESKTOP”, pulsa enter. Escribe “node index.js”
(NOTA): Es necesario tener instalado “Node.js”: (https://nodejs.org/es/)
