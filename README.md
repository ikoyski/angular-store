# Angular Store

This project was generated using [Angular CLI](https://github.com/angular/angular-cli) version 19.1.5.
Published on Github pages: https://ikoyski.github.io/angular-store/

## Development server

To start a local development server, run:

```bash
ng serve
```

Once the server is running, open your browser and navigate to `http://localhost:4200/`. The application will automatically reload whenever you modify any of the source files.

## Building

To build the project run:

```bash
ng build --configuration=production --output-path docs --base-href /angular-store/ && mv docs/browser/* docs/ && rmdir docs/browser && cp docs/index.html docs/404.html
```

This will compile your project and store the build artifacts in the `docs/` directory. By default, the production build optimizes your application for performance and speed.

