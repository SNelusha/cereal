# Getting Started

## Installation

```
npm install @snelusha/cereal
```

## Usage

```js
// Subscribe
import { subscribe } from "@snelusha/cereal";
subscribe("SUBSCRIBE_TOPIC", (payload) => console.log(payload));

// Publish
import { publish } from "@snelusha/cereal";
publish("SUBSCRIBE_TOPIC", payload);

// Unsubscribe
import { subscribe } from "@snelusha/cereal";
const unsubscribe = subscribe("SUBSCRIBE_TOPIC", (payload) =>
  console.log(payload)
);
unsubscribe();
```
