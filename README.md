# What is this?

Get shadows on boxes.

# Installation 

`npm i @emilienkopp/shadowizard --save`

Then...

```
import { shadowizard } from 'shadowizard'

shadowizard({
    shadow_type: 'soft',
    padding: false
})
```

## Options

Shadowizard supports two options, both optional:

* *shadow_type* - _hard | soft_ (Defaults to soft)
* *padding* - _boolean_ (Defaults to false)