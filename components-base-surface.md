# Surface

`<Surface>` is the most basic component of AVG.js, which is a component encapsulation of *<canvas>* tag.

```javascript
import { React, Component, core, components } from 'avg-core';
const { Surface } = components;

class Game extends Component {
  render() {
    return (
      <Surface>
      </Surface>
    );
  }
}
render(<Game />, document.getElementById('app'));

(async () => {
  await core.init(1280, 720, {
    fitWindow: true,
    assetsPath: 'assets',
    tryWebp: false
  });

  core.render(<Game />, document.getElementById('app'));

  core.start();
})();
```

The above code shows the most basic use of AVG.js (no content, black screen).

Within `<Surface>`, you can freely add other components to build the game system.
