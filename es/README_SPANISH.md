# Proyecto Whoops

Este es el repositorio GitHub para el **Proyecto Whoops**.

## Descripción

El **Proyecto Whoops** es un proyecto que involucra reproducción de videos y superposiciones. Proporciona un reproductor de video con una superposición que muestra mensajes de error e información del sistema en caso de problemas de reproducción.

## Nota importante

Al usar este proyecto, ten en cuenta lo siguiente:

- Los videos secretos tienen nombres como `secret_xx_{IDIOMA}.mp4`, donde `{IDIOMA}` debe ser reemplazado por el código de idioma correspondiente.
- No modifiques ni cambies el nombre de las carpetas de idioma. Estas carpetas son necesarias para que la página detecte los diferentes idiomas admitidos.

## Uso

Para usar el **Proyecto Whoops**, sigue estos pasos:

1. Clona el repositorio: `git clone https://github.com/Num4ersur/whoops-open-source.git`
2. Abre el archivo `index.html` en un navegador web que admita la reproducción de videos.

## Alojamiento del proyecto

Puedes alojar el **Proyecto Whoops** en varias plataformas:

- **Glitch**: Remixa el proyecto en Glitch visitando [https://glitch.com/edit/#!/import/git?url=https://github.com/Num4ersur/whoops-open-source.git](https://glitch.com/edit/#!/import/git?url=https://github.com/Num4ersur/whoops-open-source.git).
- **Replit**: Remixa el proyecto en Replit visitando [https://replit.com/github/Num4ersur/whoops-open-source](https://replit.com/github/Num4ersur/whoops-open-source).
- **Neocities**: Ten en cuenta que Neocities puede requerir un plan de pago para cargar videos. Para alojarlo usando Neocities:
  1. Descarga el archivo ZIP del proyecto desde GitHub.
  2. Inicia sesión en tu cuenta de NeoCities.
  3. Carga el archivo ZIP o extráelo en tu sitio NeoCities.
  4. Importante: Ten en cuenta que cargar videos puede requerir un plan de pago, ya que la versión gratuita de NeoCities podría no admitir la carga de videos.
- **Tinkerhost / Infinity Free**:
  1. Descarga el archivo ZIP del repositorio de GitHub.
  2. Inicia sesión en tu cuenta de Tinkerhost o Infinity Free.
  3. Accede a la sección "MY Accounts".
  4. Conéctate al FTP de tu cuenta utilizando programas FTP como [FileZilla](https://filezilla-project.org/), [Cyberduck](https://cyberduck.io/) o [WinSCP](https://winscp.net/eng/index.php).
  5. Carga los archivos del proyecto en la carpeta `.htdocs`.
  6. Precaución: El uso del plan gratuito de Tinkerhost o Infinity Free tiene un límite de 50,000 visitas. Exceder este límite podría resultar en la suspensión de tu sitio web durante 24 horas. Puedes verificar la cantidad de visitas accediendo al "Panel de control" de tu cuenta.
  7. Advertencia: Si Tinkerhost / Infinity Free detecta tu sitio web como una plataforma de intercambio de videos, podrían suspender tu sitio. Si tienes problemas de este tipo, considera contactar al [equipo de soporte de Infinity Free](https://forum.infinityfree.net/) o a [Tinkerhost](https://community.tinkerhost.net/).
  8. Advertencia final: No utilices el FTP en línea proporcionado por Tinkerhost / Infinity Free, ya que podría causar problemas. En su lugar, considera utilizar programas FTP como [FileZilla](https://filezilla-project.org/), [Cyberduck](https://cyberduck.io/) o [WinSCP](https://winscp.net/eng/index.php).
  9. Ten en cuenta que el uso de archivos de video puede requerir un plan de pago, ya que los planes gratuitos podrían no admitir la carga de videos.
  - **Vercel**: Despliega el proyecto en Vercel siguiendo estos pasos:
  1. Clona el repositorio: `git clone https://github.com/Num4ersur/whoops-open-source.git`
  2. Instala Vercel CLI (si no está instalado): `npm install -g vercel`
  3. Navega hasta la carpeta del proyecto: `cd whoops-open-source`
  4. Despliega el proyecto usando Vercel: `vercel`
- **Netlify**: Despliega el proyecto en Netlify siguiendo estos pasos:
  1. Clona el repositorio: `git clone https://github.com/Num4ersur/whoops-open-source.git`
  2. Regístrate en una cuenta de Netlify si no tienes una.
  3. Conecta tu cuenta de GitHub a Netlify.
  4. Crea un nuevo sitio desde Git y selecciona tu repositorio de GitHub.
  5. Configura las opciones de construcción y despliega el sitio.
- **GitHub Pages**: Aloja el proyecto en GitHub Pages siguiendo estos pasos:
  1. Haz push de tus cambios a la rama `gh-pages` de tu repositorio.
  2. Ve a la Configuración > Páginas del repositorio.
  3. Selecciona la rama `gh-pages` como origen y guarda.
  - **Ngrok** (Advertencia: Revela tu IP pública): Haz el proyecto público usando Ngrok y el servidor web de Python:
  1. Clona el repositorio: `git clone https://github.com/Num4ersur/whoops-open-source.git`
  2. Navega hasta la carpeta del proyecto: `cd whoops-open-source`
  3. Inicia un servidor web con Python: `python -m http.server`
     - **Windows**: Ejecuta `python -m http.server` en la línea de comandos.
     - **macOS / Linux**: Abre una terminal y ejecuta `python3 -m http.server`.
  4. Descarga y configura Ngrok desde [https://ngrok.com/download](https://ngrok.com/download).
     - **Windows**: Descarga el archivo ZIP y descomprímelo.
     - **macOS / Linux**: Descarga el archivo y mueve el ejecutable a una ubicación accesible.
  5. Ejecuta Ngrok para exponer el servidor:
     - **Windows**: Ejecuta `ngrok http 8000` en la línea de comandos.
     - **macOS / Linux**: Abre una terminal y ejecuta `./ngrok http 8000`.
  6. Advertencia: Visitar la URL de Ngrok mostrará tu IP pública. Considera usar una VPN para mayor seguridad.
  ## VPNs Recomendadas para Mayor Seguridad

Para mejorar tu seguridad y privacidad en línea al alojar tu proyecto, considera usar una Red Privada Virtual (VPN). Aquí tienes un par de opciones:

- **VPNs de Pago**:
  - ExpressVPN: Ofrece encriptación sólida y una amplia gama de ubicaciones de servidores. [Sitio web](https://www.expressvpn.com/)
  - NordVPN: Conocida por sus sólidas características de seguridad y una amplia red de servidores. [Sitio web](https://nordvpn.com/)

- **VPNs Gratuitas**:
  - ProtonVPN: Proporciona un plan gratuito limitado con encriptación segura y sin límites de datos. [Sitio web](https://protonvpn.com/)
  - Windscribe: Ofrece un plan gratuito con una generosa asignación de datos y sólidas funciones de privacidad. [Sitio web](https://windscribe.com/)

Recuerda que aunque las VPNs gratuitas son un buen punto de partida, las VPNs de pago generalmente ofrecen características más avanzadas y una seguridad más sólida. Elige la que mejor se adapte a tus necesidades y presupuesto.

Ten en cuenta que usar una VPN es solo una de las medidas para proteger tu privacidad en línea. Siempre asegúrate de usar prácticas seguras al hostear usando ngrok.


## Contribuciones

¡Damos la bienvenida a las contribuciones al **Proyecto Whoops**! Si deseas contribuir, sigue estos pasos:

1. Hacer un "fork" del repositorio.
2. Crea una nueva rama: `git checkout -b caracteristica/nueva-caracteristica`
3. Realiza tus cambios y haz un commit: `git commit -m "Agregar tus cambios"`
4. Haz push a tu repositorio bifurcado: `git push origin caracteristica/nueva-caracteristica`
5. Crea una solicitud de extracción en el repositorio principal.

## Problemas

Si encuentras problemas mientras usas el **Proyecto Whoops**, por favor repórtalos en nuestro [servidor de Discord](https://discord.gg/zgzh6REz2d).

## Licencia

Este proyecto está bajo la [Licencia MIT](LICENSE).

---

**Nota:** Este proyecto utiliza HTML, CSS y JavaScript para crear un reproductor de video con una superposición para mensajes de error e información del sistema. El reproductor de video carga y reproduce automáticamente videos, pero también verifica la compatibilidad con el navegador. Por favor, sigue las instrucciones de alojamiento de arriba si deseas implementar el proyecto en diferentes plataformas.
