# A Todo app with "no" dependencies

## That being said, the dependencies are

* A _new_ Node version, because this is using [experimental modules](https://nodejs.org/api/esm.html)
* A decent browser

## Rules

* Focus on learning
* No additional dependencies. A custom solution for everything. How hard can it be?
* Keep the domain super simple, unless X-requirement opens up an interesting problem you would like to learn about
* Don't prematurely overengineer, unless, of course, you want to learn

## Requirements

* Todos should not be lost easily
* Fast
* UI is also very fast
  * Optimistic updates (everywhere?)

## Running

```
node --experimental-modules index.mjs
# OR
bin/node index.mjs
```

## Testing

```
node --experimental-modules testAll.mjs
# OR
bin/node testAll.mjs
```
