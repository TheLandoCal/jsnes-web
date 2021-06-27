# JSNES Web UI

An NES web emulator built with [JSNES](https://github.com/bfirsh/jsnes) and [JSNES Web UI](https://github.com/bfirsh/jsnes-web).

## Development Guide

All steps to run and build JSNES using `npm` will be outlined below.

### Local Development

`npm` scripts can be used for standard development processes. Refer to [package.json](package.json) for full implementation details.

| Command               | Description                                                      |
| --------------------- | ---------------------------------------------------------------- |
| `npm install`         | Install/Update package dependencies                              |
| `npm start`           | Run a local version of the React application                     |
| `npm run format`      | Manually format all code using Prettier (required for build)     |
| `npm run test`        | Interactively run tests (via jest)                               |
| `npm run build`       | Optimize code for production environment                         |
| `npm run serve`       | Serve the build from a static local server (assume build exists) |
| `npm run build:serve` | Build + Serve                                                    |

## License

This project is licensed under the [Apache License 2.0](https://choosealicense.com/licenses/apache-2.0/).
See [LICENSE](LICENSE) for more information.
