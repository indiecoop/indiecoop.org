# IndieCoop

Source for IndieCoop site: __https://indiecoop.org/__


## Installation

1. Clone the repo:

    ```sh
    git clone git@github.com:indiecoop/indiecoop.org.git && cd indiecoop.org
    ```

2. Install the Node dependencies:

    ```sh
    npm install
    ```

## Development

Serve the site from the simple server:

```sh
npm start
```

(Or run this aliased command, `npm run dev`, if you'd prefer.)

Then launch the site from your favorite Web browser:

[__http://localhost:4000/__](http://localhost:4000/)

If you'd like, you can serve the site from a different port:

```sh
PORT=8000 npm start
```

To work on your own changes, fork the [origin repository](https://github.com/indiecoop/indiecoop.org).


## Deployment

To deploy the site to [production](https://indiecoop.org/) (served from [GitHub Pages](https://pages.github.com/)):

```sh
npm run deploy
```

To work on your own changes, fork the [origin repository](https://github.com/indiecoop/indiecoop.org).

To deploy the site to __your__ fork's GitHub Pages (e.g., https://cvan.github.io/indiecoop/):

```sh
npm run deploy cvan
```
