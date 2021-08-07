## This is a test repository of [react-countdown-circle-timer](https://github.com/vydimitrov/react-countdown-circle-timer)

### How to use it

`npm i react-countdown-circle-timer`

- import
```diff
import { CountdownCircleTimer } from 'react-countdown-circle-timer'
```

- useing
```diff
  <CountdownCircleTimer
    isPlaying
    duration={10}
    colors={[
      ['#004777', 0.33],
      ['#F7B801', 0.33],
      ['#A30000', 0.33],
    ]}
  >
    {({ remainingTime }) => remainingTime}
  </CountdownCircleTimer>
```

####  "dependencies"
  - "react-countdown-circle-timer": "^2.5.3",

