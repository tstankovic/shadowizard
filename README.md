# What is this?

Get perfect shadows every time for the non-designer.

# Installation

`npm i shadowizard -D`

Then...

```
import { shadowizard } from 'shadowizard';

shadowizard({
  shadow_type: 'soft',
  padding: false
});
```

## Options

Shadowizard supports 2 options, both of which are optional:

- _shadow_type_ - _hard | soft_ (Defaults to soft)
- _padding_ - _boolean_ (Defaults to false)
