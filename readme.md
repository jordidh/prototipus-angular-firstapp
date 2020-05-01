# Bibliografia
https://angular.io/start


# DESENVOLUPAMENT

## Crear un projecte nou
If you go directly to the StackBlitz online development environment and choose to start a new Angular workspace, you get a generic stub application

## Angular
Una aplicacióó Angular s'organitza en un arbre de components. Cada compoent té una responsabilitat especíífica.
També hi ha servies, són classes disponibles a qualsevol part de l'aplicació gracies a la injecció de dependències. Serveixen per compartir dades entre les parts de l'aplicació.

### Components
Els components encapsulen arees de responsabilitat de la IU, permet reutilitzar funcionalitat.
Es componen de 3 elements:
* Classe component: Gestiona dades i funcionalitat
* Template HTML: defineix la UI
* Estils del component: defineixen l'estil
Els components es poden comunicar entre ells de diferent manera: https://angular.io/guide/component-interaction

### Templates (html)
Elements dels template (html) https://angular.io/guide/template-syntax 
Directives estructurals: comenen per *, modifiquen l'estructura del DOM, p.e.:
* <div *ngFor="let product of products">...</div>
* <p *ngIf="product.description">...</p>
Interpolation: {{}} renderitza el valor de la propietat com un text
Property binding: [] permet fer servir el valor d'una propietat en una expressió del template
Event binding: () permet vincular un event en un element

### Serveis
https://angular.io/guide/architecture-services

### Forms in Angular

### Routing
https://angular.io/start/start-Routing
https://angular.io/guide/router

S'afegeixen les rutes al mòdul principal, app.module.ts. S'indica la ruta i el component que s'executaràà

# DESPLEGAMENT

Procés de desplegament:
* Descarregar el projecte de Stackblitz a una màquina local
* Compilar el projecte i generar els elements JavaScript, CSS i HTML
* Hostatjar els elements JavaScript, CSS i HTML en un servidor web

