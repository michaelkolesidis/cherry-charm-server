# Cherry Charm Server 🍒

The server of [Cherry Charm](https://github.com/michaelkolesidis/cherry-charm).

## Instructions

**1.** Install the project dependencies:

```
yarn
```

**2.** Start the server:

```
yarn start
```

**3.** Start the frontend, following the instructions in the [Cherry Charm](https://github.com/michaelkolesidis/cherry-charm) repository.

## Features

The server offers a single API endpoint that returns an array of three values chosen randomly.

Given the significance of security in the online gaming industry, where safeguarding fairness and integrity is paramount, to achieve secure random number generation, the server relies on the [Crypto](https://nodejs.org/api/crypto.html#crypto) module of Node.js. It is specifically designed to utilize cryptographic algorithms and system-level entropy sources, ensuring the production of random output that is suitable for cryptographic operations and resistant to various attacks.

Since it is possible for Node.js to be built without including support for the `node:crypto` module, it is checked whether the module is available. If that is not the case, the service will fall back to using [Math.random()](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Math/random) for generating random numbers.

## Technologies

The core technologies of _Cherry Charm Server_ are Node and [CORS](https://en.wikipedia.org/wiki/Cross-origin_resource_sharing). The following libraries and tools are used:

| Name       | License | Description                                                     |
| ---------- | :-----: | --------------------------------------------------------------- |
| TypeScript |   MIT   | A strongly typed programming language that builds on JavaScript |
| Node.js    |   MIT   | Cross-platform JavaScript runtime environment.                  |
| Express    |   MIT   | Backend framework for building RESTful APIs with Node.js        |
| CORS       |   MIT   | Node.js CORS middleware                                         |

## See Also

- [Cherry Charm](https://github.com/michaelkolesidis/cherry-charm)

## License

<a href="https://www.gnu.org/licenses/agpl-3.0.html"><img src="https://upload.wikimedia.org/wikipedia/commons/0/06/AGPLv3_Logo.svg" height="100px" /></a>

Copyright (c) 2023 Michael Kolesidis<br>
Licensed under the [GNU Affero General Public License v3.0](https://www.gnu.org/licenses/agpl-3.0.html).

🍒
