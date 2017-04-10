# js-react-patterns
Les principaux patterns utilisés avec React

### Les essentiels

React est une librairie JavaScript **orientée composant** . Un composant React comprend le markup HTML, le script JS et le style CSS. Le but est de pouvoir réutiliser les composants dans l'application et éventuellement dans d'autre projet.

**Composition** : Ecrire un composant qui "wrap" des elements HTML ou REACT. Le principe est d'utiliser this.props.children pour recuperer les elements contenus afin de les utiliser à l'intérieur du container. (ex. styling components ou styled component)

**HOC (High Order Component)** : Ecrire une fonction qui prend en parametre un composant afin de le retourner dans un contexte étendu. Les HOC remplace le concept de mixin des anciennes versions de react.

**Presentationnal components** (ou dumbs components / ou stateless components) : la plupart des composant React n'ont pas besoin de state interne

### références :

https://github.com/krasimir/react-in-patterns
https://github.com/planningcenter/react-patterns
http://reactpatterns.com/
