# Curso de Diseño de Apps
## Qué es una App
Una app es una aplicacion de software que se instala en dispositivos moviles o tablets para **ayudar al usuario en una labor concreta**, ya sea de caracter profesional o de ocio y entretenimiento.

Las tiendas de aplicaciones penalizan las apps que se suban que tengan el mismo código, por ejemplo, una empresa vende la misma aplicación de venta de pantalones a dos empresas diferentes. No solo valoran código, sino contenidos y funcionalidad. En el desarrollo en iOS recomiendan subir la aplicación un mes antes para tenerla lista para cuando el cliente quiera.

> **Pixel perfect:** Se coge la aplicación desarrollada y se coge el diseño que se pasó a los desarrolladores, se comparan y se comprueba que todo está tal cual se diseñó.

### Web App
- Todos los usuarios usan la misma versión.
- No es necesario instalar una app en el dispositivo.
- Un único desarrollo para todas las plataformas.
- No se puede usar sin acceso a internet.

### Nativa
- Ofrecen el mejor rendieimiento al utilizar los SDK oficiales.
- Acceso a todos los componentes SW y HW.
- Mejor experiencia de usuario.
- Un desarrollo diferente por plataforma, Más caro de desarrollar inicialmente.

### Híbrida
- Portabilidad: código unico para todas las plataformas.
- Más barato al poder desarrollar un único código para todas las plataformas
- Mala experiencia de ususario acceso limitado a los componentes SW y HW, limitado al desarrollado de una plataforma ajena a los SDKs oficiales, más dificil de mantener.  


## Guías de diseño
Los usuarios de cada plataforma quieren y buscan cosas distintas. Tenemos que innovar, ser creativos pero no reinvernar la rueda. Los comportamientos de los usuarios con las aplicaciones no hay que reinventarlas. Antes de ponerse a diseñar, hay que cuesitionarse como lo hace la plataforma por defecto, analizar lo que hay y ver las buenas prácticas de cada plataforma (contenidas en las guías de diseño de cada una). Tener en cuenta que estas guías también ofrecen recursos para descargar y utilizarlos en los rogramas de diseño. Ayuda mucho a saber argumentar las decisiones de diseño, básicamente porque lo que viene aquí es indiscutible, además de que queda bien de cara al cliente.

## ¿Qué preguntas debemos hacernos antes de empezar?
- **Tecnología**: nativa, híbrida(¿framework?) o web app.
- **Plataforma**: iOS, Android, Windows 10.
- **Dispositivo**: móvil, tablet, watch, tv, coche.
- **Multidispositivo**: móvil y tablet a la vez, que permita reutilizar elementos.
- **Versión**: librerías e interacciones soportadas a partir de cierta versión.
- **Usuario**: distintos perfiles y nivel de experiencia con lo digital.  
- **Contexto de uso**: herramienta de trabajo o de ocio, dónd e se va a utilizar y cómo.
- **Expectativas**: entender qué es lo que el cliente espera recibir y qué es lo que se le ha vendido en realidad.
- **Exclusividad**: quieren una app estándar o exclusiva, depende de cuánto quieran alejarse de lo normal en una aplicación o innovar.
- **Contenido**: ¿todo es importante? ¿hay que incluirlo todo?

## Puntos críticos
- **Menús**: decisión conjunta, hamburger o tab bar. Si ahora tengo 5 opciones pongo un tab bar, pero si el dia de mañana ponen una funcionalidad nueva es un lío. Conviene buscar un compromiso.
- **Ser fieles a cada plataforma**: hacer caso a las guías de cada plataforma o hacer lo mismo en todas.
- **Arquetipos de las personas**: nivel de interacción y familiarización con los dispositivos.
- **Apps de referencia**: en lo workshops iniciales conviene llevar ejemplos, tanto malos como buenos, para que el cliente sepa hacia dónde quiere guiarse.
- **Desconocimiento**: hay clientes que no saben lo que es una app bien hecha.

> **Hay que saber qué guerras quieres ganar**. El cliente al principio te va a querer cuestionar todo y a lo mejor conviene pararse a discutir en cosas más cruciales como la navegación que en detallitos en botones. Con el tiempo, el cliente ganará confianza y te dejará hacer más cosas, y al final vas a poder tener la posibilidad de lucirte haciendo mejores aplicaciones gracias a esta confianza. - Isabel.
