# Vue2 - Module Federation Demo

This example demos consumption of federated modules from a rollup bundle. `host-simple` app depends on a component exposed by `remote-simple` app.

## Running Demo

Run `pnpm`, `pnpm build` and `pnpm serve`. This will build and serve both `host-simple` and `remote-simple` on ports 5000, 5001 respectively.

- HOST (host-simple): [127.0.0.1:5010](http://127.0.0.1:5000/)
- REMOTE (remote-simple): [127.0.0.1:5011](http://127.0.0.1:5001/)

`CTRL + C` can only stop the host server. You can run `pnpm stop` to stop all services.
