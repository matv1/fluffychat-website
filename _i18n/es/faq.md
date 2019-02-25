# Preguntas frecuentes

*   [Configuración de la cuenta](#configuracion-de-la-cuenta)
*   [Comenzar a chatear](#comenzar-chat)
*   [Configuración del chat](#configuracion-chat)
*   [Pasarela a otros sistemas de chat](#pasarela-a-otros-sistemas-de-chat)
*   [Gestión de errores](#gestion-errores)
*   [Acerca de FluffyChat](#acerca-de-fluffychat)

## Configuración de la cuenta <a id="configuracion-de-la-cuenta"></a>

#### ¿Cómo puedo restablecer mi contraseña?

Debe conectar una dirección de correo electrónico a su cuenta. Se puede hacer en la configuración de la cuenta. Si no tiene conectada una dirección de correo electrónico, tiene que contactar con el soporte de su «homeserver» (servidor de datos).
 ([¿Qué es un «homeserver» (servidor de datos)?](#Quéesunhomeserver))  
[Pulse aquí para restablecer su contraseña](https://www.ubports.chat/#/forgot_password).

#### ¿Cómo puedo crear una nueva cuenta?

1.  Si ya ha iniciado sesión en FluffyChat, vaya a configuración y pulse en «cerrar sesión» en la parte inferior.
2.  Elija un nuevo nombre de usuario y compruebe que está seleccionado «crear una cuenta».
3.  Si quiere crear una cuenta en un «homeserver» (servidor de datos) distinto al predeterminado (ubports.chat), vaya al menú superior de la izquierda y cambie el «homeserver» (servidor de datos). ([¿Qué es un «homeserver» (servidor de datos)?](#Quéesunhomeserver))
4.  Vaya a «iniciar sesión» y elija una nueva contraseña.

#### ¿Cómo puedo iniciar sesión en mi cuenta antigua?

1.  Si ya ha iniciado sesión en FluffyChat, vaya a configuración y pulse en «cerrar sesión» en la parte inferior.
2.  Introduzca el nombre de usuario o la identificación («ID») de Matrix de su cuenta antigua. ([¿Qué es una identificación («ID») de Matrix?](#QuéesunaIDdeMatrix)) Si no recuerda su nombre de usuario o su identificación («ID») de Matrix pero recuerda el número de teléfono conectado con su cuenta, entonces puede introducir cualquier nombr de usuario y el número de teléfono correcto en el siguiente paso. El nombre de usuario será localizado automáticamente.
3.  (Opcional) Introduzca el número de teléfono de su antigua cuenta.
4.  Si su cuenta antigua no está en el «homeserver» (servidor de datos) predeterminado (ubports.chat), vaya al menú superior de la izquierda y cambie el «homeserver» (servidor de datos). ([¿Qué es un «homeserver» (servidor de datos)?](#Quéesunhomeserver))
5.  Asegúrese de que «crear una cuenta» **no** está marcado.
6.  Vaya a «iniciar sesión» e Introduzca su contraseña. ([¿Contraseña olvidada?](#Comopuedorestablecermicontraseña))

#### ¿Qué es una identificación («ID») de Matrix?

Su «ID» de Matrix es su identificador único en la red de Matrix. Es una combinación de su nombre de usuario y de su «homeserver» (servidor de datos). ([¿Qué es un «homeserver» (servidor de datos)?](#Quéesunhomeserver))  
El formato de una identificación («ID») de Matrix es sencillo: @nombredeusuario:homeserver. Por ejemplo, si su nombre de usuario es «alicia» y su «homeserver» (servidor de datos) es «homeserver.abc», entonces su («ID») de Matrix es: @alicia:homeserver.abc

#### ¿Qué es un «homeserver» (servidor de datos)?

Matrix es una red federada de «homeservers» (servidores de datos). ¿Qué significa esto? No hay un «servidor de FluffyChat» centralizado pero existen muchos «homeservers» (servidores de datos) que puede usar. Es libre para elegir el que quiera. Al igual que ocurre con el correo electrónico, todos los servidores se comunican entre ellos. Existe un «homeserver» (servidor de datos) predeterminado en FluffyChat llamado «https://ubports.chat». También puede alojar su propio servidor. [Pulsar aquí para la guía de como comenzar](https://matrix.org/docs/guides/installing-synapse).

#### ¿Qué es un servidor de identidad?

Los usuarios en Matrix son identificados internamente vía un «ID» de Matrix. Sin embargo, identificadores actuales de terceras partes («3PID») como las direcciones de correo electrónico o los números de teléfono deberían usarse públicamente para identificar a los usuarios de Matrix, al menos para las invitaciones. Una «identidad» de Matrix describe tanto el «ID» del usuario como cualquier otros «IDs» de terceras partes enlazadas a sus cuentas.  
Los usuarios de Matrix pueden enlazar «IDs» de terceras partes («3PIDs») a sus «ID» de usuario. Enlazando «3PIDs» se crea un mapeo desde un «3PID» a un «ID» de usuario. Este mapeo puede luego ser usado por los usuarios de Matrix para descubrir los «MXIDs» de sus contactos. Para asegurar que el mapeo desde el «3PID» a un «ID» de usuario es genuino, la intención es que haya un grupo globalmente federado de servidores de identidad («IS») de confianza para usarlo para verificar el «3PID» y continuar y replicar los mapeos. No se necesita el uso de un «IS» para que una aplicación cliente sea parte del ecosistema de Matrix. Sin embargo, sin un cliente no será capaz de buscar «IDs» de usuario usando «3PIDs».

## Comenzar a chatear <a id="comenzar-chat"></a>

#### ¿Cómo puedo comenzar un nuevo chat?

1.  Vaya al botón "+" en la página de inicio o deslice desde abajo en el dispositivo.
2.  Elija los contactos que quiere invitar a su nuevo chat. No es necesario invitar a alguno.
3.  Si no encuentra un contacto, puede [añadirlo por el número de teléfono](#Cómopuedoañadircontactosporsunúmerodeteléfono) o introducir su «ID» de Matrix en el campo de búsqueda. (¿Qué es una identificación («ID») de Matrix?](#QuéesunaIDdeMatrix))
4.  Vaya a «crear chat»
5.  Si desea crear un chat directo con un contacto, simplemente seleccione un contacto o toque el avatar y vaya a «Iniciar chat directo».

#### ¿Cómo puedo unirme a un chat público?

Un chat público tiene una o más direcciones públicas llamadas «alias». Siempre empiezan con «#» y terminan con «:homeserver.abc». Por ejemplo: [#fluffychat:matrix.org](fluffychat://#fluffychat:matrix.org). Solo pulse en el enlace para participar en el chat o introduzca un alias en el campo de búsqueda en la página de inicio de FluffyChat.

#### ¿Cómo puedo unirme a una comunidad?

Una comunidad pública tiene una o más direcciones públicas llamadas «alias». Siempre empiezan con «+» y terminan con «:homeserver.abc». Por ejemplo: [+ubports\_community:matrix.org](fluffychat://+ubports_community:matrix.org). Solo pulse en el enlace para ver todos los chats asociados con una comunidad. Para más detalles, visite la [aplicación web de escritorio](https://www.ubports.chat).

#### ¿Cómo puedo añadir contactos por su número de teléfono?

1.  Vaya al botón «+» en la página de inicio o deslice desde abajo en el dispositivo.
2.  Vaya a «añadir contacto» en la parte superior de la izquierda.
3.  Elija su aplicación de agenda.
4.  Seleccione el contacto que desee añadir o seleccione todos los contactos y confirme.
5.  FluffyChat buscará esos contactos en el servidor de identidad. ([¿Qué es un servidor de identidad?](#Quéesunservidordeidentidad))

#### ¿Qué «/órdenes» están disponibles?

*   «/me» (Enviará «msgtype: m.emote») Muestra una acción.
*   «/whisper» (Enviará «msgtype: m.fluffychat.whisper») El texto del mensaje será muy pequeño
*   «/roar» (Enviará «msgtype: m.fluffychat.roar») El texto del mensaje será muy grande, en negrita y mayúsculas
*   «/shrug» Coloca «¯\\(ツ)/¯» al inicio del mensaje

## Configuración del chat <a id="configuracion-chat"></a>

#### How can I kick or ban a user from a chat?

You need the permission to kick or ban a user from a chat.

1.  Go to the chat
2.  Go to "Chat infos" in the top right menu
3.  Find the user you want to kick or ban and swipe the user list item to the right.
4.  Click on the kick or the ban button and confirm

#### How can I change the user permissions in a chat?

You need the permission to change the user permissions.

1.  Go to the chat
2.  Go to "Chat infos" in the top right menu
3.  Find the user you want to kick or ban and swipe the user list item to the left.
4.  Click on the desired user permission button and confirm

#### How can I change the chat topic and description?

You need the permission to change the chat topic and description.

1.  Go to the chat
2.  Go to "Chat infos" in the top right menu
3.  Click on the top right edit button and enter the desired chat topic and/or description

#### How can I edit the chat privacy settings?

You need the permission to edit the chat privacy settings.

1.  Go to the chat
2.  Go to "Chat infos" in the top right menu
3.  Go to "Privacy and security"
4.  Toggle or untoggle the desired options and edit the user permission options

#### What are chat aliases and how can I edit them?

Chat aliases are public chat addresses which can be used to join a chat. You need the chat permissions to change them.

1.  Go to the chat
2.  Go to "Chat infos" in the top right menu
3.  Go to "Privacy and security"
4.  Toggle or untoggle the desired options and edit the user permission options

#### How can I send animated stickers with Giphy?

1.  Start a new chat with [@neb\_giphy:​matrix.org](fluffychat://@neb_giphy:​matrix.org).
2.  Search for gifs by typing: '!giphy KEYWORD'
3.  Add an animated sticker by clicking on the sticker and add it to your local sticker collection by clicking on the "+" on the rop right.

## Bridge to other chat systems <a id="pasarela-a-otros-sistemas-de-chat"></a>

#### ¿Qué es Matrix?

Matrix is an open standard for interoperable, decentralised, real-time communication over IP. It can be used to power Instant Messaging, VoIP/WebRTC signalling, Internet of Things communication - or anywhere you need a standard HTTP API for publishing and subscribing to data whilst tracking the conversation history.

#### How can I enter a XMPP multi-user chat?

The easiest way currently is to use the bridge on matrix.org.  
Every XMPP multi-user chat has a Jabber identifier (JID) with the format: `chatname@chat.server.abc`  
The chatname is the **local** part and the chat.server.abc is the **server** part. You can enter this chat by entering the Matrix public room: `#_xmpp_server_local:matrix.org` ([How can I join a public chat?](#HowcanIjoinapublicchat))  
For the given example this would be: `#_xmpp_chat.server.abc_chatname:matrix.org`

#### How can I enter an IRC node on Freenode?

If you want to enter the node `#chatname` on freenode you can just join the public chat: `#freenode_#chatname:matrix.org`  
Replace `#chatname` with the node you want to join and you are in.

#### How can I bridge a group chat with a Telegram group chat?

Look at the tutorial on [wayneoutthere.com](https://wayneoutthere.com/how-to-bridge-matrix-telegram/).

## Gestión de errores <a id="gestion-errores"></a>

#### Why don't I receive push notifications?

Do you have an Ubuntu One account in the system settings?  
When you go into fluffychat -> Settings -> Notifications -> Targets: Is there a device "UbuntuPhone"?  
Have you tried to logout and login?  
Do you have the latest version of FluffyChat installed from the OpenStore?  
Have you tried to turn airplaine mode on and off again? Sometimes notifications are sent with a delay from the UBports push service (will be fixed soon) If you still have the problem, then please contact me at the room: [#fluffychat:matrix.org](fluffychat://#fluffychat:matrix.org)

#### Why can't I connect with port 8448?

Sorry! confused On port 8448 the most homeservers use a different ssl certificate, which causes an error. Currently the xmlhttprequest in QML does not allow those certificates.

#### ¿Por qué no puedo conectar con un certificado auto-firmado?

El mismo problema... Le recomiendo que use un certificado de Let's Encrypt.

## Acerca de FluffyChat <a id="acerca-de-fluffychat"></a>

#### ¿Cómo se financia FluffyChat?

FluffyChat es financiado por la comunidad. Puede apoyar a FluffyChat en [Patreon](https://www.patreon.com/krillechritzelius) o [Liberapay](https://liberapay.com/KrilleChritzelius)
