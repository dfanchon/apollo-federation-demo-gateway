# apollo-federation-demo-gateway

## Installation

1. Clone the repo including the submodules

```sh
git clone --recursive
```

2. Download the submodules

```sh
git submodule update --init --recursive
```

or 

```sh
git submodule update --init --recursive -j 8 to to fetch 8 submodules at the same
```

3. Start all the micro-services at once

```sh
npm run start-services
```

4. Start up the gateway

```sh
npm run start-gateway
```

