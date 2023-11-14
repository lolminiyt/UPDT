| Herramientas |
| :-: | 
| [✔️ **Minecraft**](/minecraft.md) | 

# Descargar juegos 

La pagina que recomiendo es https://cs.rin.ru/forum/, tiene mucha informacion sobre juegos, programas, y lo mas importante, juegos clean de steam

- Primero se crean una cuenta ya que sin esta no se podran ver los enlaces ni archivos

Ahora, la parte importante es ***___Steam Content Sharing___***, este incluye la mayoria de juegos sin piratear.

(Recuedo, la contraseña de los links de descarga es ~~cs.rin.ru~~ )
### Advertencia

Este metodo que voy a explicar solo se puede hacer con juegos que tengan drm de steam.
Si incluye otro tipos de metodos, como denuvo o ea play, se tienen que descargar el juego completo con el crack.

Para verificar esto, se puede consultar steam, usualmente en la store de la pagina avisa con un mensaje en amarillo el tipo de drm que tiene
### Extraer juego

Cuando se descomprima seguro pide contraseña (la misma del link de descarga).     
 Cuando se extraiga seguro aparece asi: X\steamapps\common\X

### Crackear el juego

Ahora el paso mas importante, piratearlo.
Para eso descargar: https://mr_goldberg.gitlab.io/goldberg_emulator/, donde dice Latest Release.

- Cuando se descomprima esta herramienta, buscar en \tools el generate_interfaces_file.exe 
- Ahora, toca buscar en la carpeta del juego un dll llamado steam_api64.dll o steam_api.dll, principalmente estan donde se encuentra el .exe o \nombredeljuego_Data\Plugins
- Arrastrar el steam_api64.dll (Si no se encuentra, steam_api.dll) al generate_interfaces_file.exe
Esto nos generara un archivo necesario para compatibilidad
- - - 
- Ahora, si no se encuentra steam_appid.txt donde estan los dll, crear el archivo y poner el id de la app (Si se busca el nombre del juego en steam, sale en la url Ej: https://store.steampowered.com/app/1293830/Forza_Horizon_4/, donde el appid seria 1293830)
- - - 
Por Ultimo, el CRACK.

- Del goldberg_emulator, copiar steam_api.dll y steam_api64.dll, y reemplazar todos los dll del juego sin piratear con las de goldberg

Con eso ya estaria!!!!!!!!!!!!!!

- - - 

# Solucionar fallos

### El juego me lleva a steam cuando lo abro
Esto puede ser por 2 cosas, o el crack esta mal aplicado, o todavia queda un drm, un drm incluido en el .exe del juego

Para el segundo, esto seria la solucion: 
- Descargar https://github.com/atom0s/Steamless/releases/download/v3.1.0.3/Steamless.v3.1.0.3.-.by.atom0s.zip
- Abrir Steamless.exe y arrastrar el .exe del juego
- Darle a unpack file, si este tenia drm incluido en el .exe, no deberia fallar y poner un mensaje en rojo.
- En la ruta donde estaba el .exe original, se deberian haber creado 2 .exe. 
algo llamado como  .exe.unpacked 

### Google Drive Bypass
Continuando, Algunos de los juegos estan subidos a google drive 
 - (Si el juego no se actualiza, podria ser que los links de google drive esten expirados)
Para descargar de google drive, este la mayoria de veces estara bloqueado, para evitar esto, se necesita crear un acceso directo en una carpeta vacia.

![alt text](https://i.ibb.co/fYYFXJn/imagen.png)

Despues de esto, a la carpeta donde guardaron el acesso directo, le dan click derecho y le dan a descargar, deberia de empezar a comprimir y luego descargarse.
