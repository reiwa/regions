# @reiwa/regions

List of all regions supported by Cloud Functions.

```
$ yarn add @reiwa/regions
```

## Usage

https://firebase.google.com/docs/functions/locations?hl=en#selecting-regions_firestore-storage

```
import { ASIA_NORTHEAST1 } from '@reiwa/regions

module.exports = region(ASIA_NORTHEAST1).onRun(handler)
```
