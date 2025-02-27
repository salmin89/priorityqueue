A very simple and lightweight Priority Queue, based on [this article](https://www.geeksforgeeks.org/implementation-priority-queue-javascript/).

Focused on accessibility rather than performance.

## Installation

```sh
npm i @nermin99/priorityqueue
```

## Import

```js
import { PriorityQueue } from '@nermin99/priorityqueue'
```

or

```js
const { PriorityQueue } = require('@nermin99/priorityqueue')
```

## Basic Usage

```js
const pq = new PriorityQueue()

pq.enqueue(1, 30)
pq.enqueue(2, 10)
pq.enqueue('x,y', 20)

pq.dequeue()  // { key: 2, priority: 10 }
pq.front()    // { key: 'x,y', priority: 20 }
pq.rear()     // { key: 1, priority: 30 }
```

## API

- enqueue()
- dequeue()
- front()
- rear()
- isEmpty()
- entries()
- keys()
- priorities()
