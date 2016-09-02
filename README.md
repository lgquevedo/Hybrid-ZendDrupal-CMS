# Hybrid-ZendDrupal-CMS
## Sistema manejador de contenidos basado en Zendframework 2.3 e inspirado en Drupal
### Principios generales
1. Estabilidad y escalabilidad en todas sus versiones: todo lo que funcione en su primera versión, deberá poder funcionar sin cambios en cualquier versión o mejora, a no ser que, el hardware lo haga imposible.
2. Será facilmente extensible, y podrá ser usado sin escribir una sola línea de código.
3. Será desarrollado 100% en php usando zendframework como plataforma de desarrollo.
4. Será liviano y portable. No obligará a contratar servicios de proveedores con gran infraestructura para correr, apuntará a ser de utilidad a quienes no pueden o no quieren contratarlos, particularmente pymes, que deben usar servicios de hosting compartido en los que resulta un exabrupto hacer preload de cientos o miles de clases y objetos que no van a ser usados en sus transacciones normales.
### Características a ofrecer
1. Instalación y configuración simples
2. Abstracción de bases de datos
3. manejo de ajax integrado
4. control de sesiones y seguridad
5. extensión por adición de carpetas de módulo tal como drupal basta copiar la carpeta a un directorio y activarlo con un click sin necesidad de hacer cambios en ningún archivo de sistema.
6. idealmente, todo tema que funcione en d6 o d7 debe funcionar sin cambios (eso asegura usabilidad y brinda mercado potencial)
7. rutas amigables, se atrapan 4: /setup[/:x] , /admon[/:x] y /contenido[/:x] (hasta 10 niveles de profundidad) para tareas normales y /solicitudajax[/:x] para manejo centralizado de ajax; las demás quedan disponibles para quién desee extender usando los mecanismos tradicionales de zendframework
8. otras: se esperan sugerencias

