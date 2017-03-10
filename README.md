## Install
```bash
$ yarn add actioncable-esm
# or
$ npm i --save actioncable-esm
```

## Usage
```js
import ActionCable from 'actioncable-esm'

var cable = ActionCable.createConsumer('ws://*/websocket')

cable.subscriptions.create('AppearanceChannel', {
  // normal channel code goes here...
})

export default cable
```
