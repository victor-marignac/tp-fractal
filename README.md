## Installation

_Note : il est conseillé d'effectuer un fork de ce repository pour travailler sur votre propre version_

```
npm install
npm run build
npm run fractal
```

Vous pouvez désormais voir le styleguide dans l'URL fournie par la console. Les styles ne sont cependant pas encore appliqués (absence du CSS).

Dans un autre terminal, lancez :

```
npm run dev
```

Le styleguide est désormais stylisé et se recharge lorsque le CSS est mis à jour.

## Ressources

### Atomic Design

- [Atomic Design by Brad Frost](https://atomicdesign.bradfrost.com/chapter-2/)
- [Design Tokens](https://medium.com/eightshapes-llc/tokens-in-design-systems-25dd82d58421)

### Design systems

- [City of Ghent](https://stijlgids.stad.gent/v3/components/detail/header.html)
- [Mailchimp](http://ux.mailchimp.com/patterns/icons)
- [Firefox](https://protocol.mozilla.org/)
- Une longue liste [ici](https://designsystemsrepo.com/design-systems/) !

### Les outils

- [StoryBook](https://storybook.js.org/)
- [PatternLab](https://patternlab.io/)
- [Fractal](http://fractal.build/)

### BEM

- [BEM Cheat Sheet](https://9elements.com/bem-cheat-sheet/?utm_source=CSS-Weekly&utm_campaign=Issue-406&utm_medium=web)

### Atomic Design + BEM

- Atom : `a-block__element--modifier`
- Molecule : `m-block__element--modifier`
- Organism : `o-block__element--modifier`
- Layout : `l-block__element--modifier`
