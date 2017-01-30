# kframe

![kframe](https://cloud.githubusercontent.com/assets/674727/15790659/69860590-2987-11e6-9511-65c28e583c6f.png)

Kelvin's collection of A-Frame components and scenes.

[VIEW DEMOS](http://kelvin-lightner.com/LiveH2H/)

## Components

See documentation for individual components:

- [animation](https://github.com/ngokevin/kframe/tree/master/components/animation/) - Animations in A-Frame using anime.js
- [audioanalyser](https://github.com/ngokevin/kframe/tree/master/components/audioanalyser/) - Audio visualizations in A-Frame using Web Audio (AnalyserNode)
- [broadcast](https://github.com/ngokevin/kframe/tree/master/components/broadcast/) - Multi-user in A-Frame using raw websockets
- [entity-generator](https://github.com/ngokevin/kframe/tree/master/components/entity-generator/) - Generate a number of entities in A-Frame given a mixin
- [event-set](https://github.com/ngokevin/kframe/tree/master/components/event-set/) - Set properties in response to events in A-Frame
- [firebase](https://github.com/ngokevin/kframe/tree/master/components/firebase/) - Multi-user in A-Frame using Firebase
- [layout](https://github.com/ngokevin/kframe/tree/master/components/layout/) - Position and layout child entities in 3D space for A-Frame
- [look-at](https://github.com/ngokevin/kframe/tree/master/components/look-at/) - Rotate an entity to face towards another entity in A-Frame
- [mountain](https://github.com/ngokevin/kframe/tree/master/components/mountain/) - Mountain terrain in A-Frame using randomly-generated height maps
- [randomizer](https://github.com/ngokevin/kframe/tree/master/components/randomizer/) - Randomize color, position, rotation, and scale in A-Frame
- [redux](https://github.com/ngokevin/kframe/tree/master/components/redux/) - Hook in Redux reducers, data bindings, and action dispatches for A-Frame
- [reverse-look-controls](https://github.com/ngokevin/kframe/tree/master/components/reverse-look-controls/) - Fork of A-Frame v0.3.0 look controls component with reversed mouse drag.
- [sun-sky](https://github.com/ngokevin/kframe/tree/master/components/sun-sky/) - Gradient sky with adjustable sun in A-Frame
- [template](https://github.com/ngokevin/kframe/tree/master/components/template/) - Encapsulate groups of entities, use templating engines, and do string interpolations in A-Frame
- [text](https://github.com/ngokevin/kframe/tree/master/components/text/) - Geometry-based text in A-Frame
- [webvr-recorder](https://github.com/ngokevin/kframe/tree/master/components/webvr-recorder/) - A-Frame component to record WebVR pose and events to localStorage or JSON. Then replay them without needing VR.


## Local Installation

Go to the folder of the component or scene you wish to develop and check out
its README. Generally the steps involve:

```bash
git clone git@github.com:ngokevin/kframe && cd kframe
# Head to the folder to develop (e.g., `cd components/foo`, `cd scenes/foo`).
npm install
npm run dev  # (or sometimes `npm run start`)
```

Then a page should open in your browser. You can develop on the source code and
the server will handle live compilation and bundling.
