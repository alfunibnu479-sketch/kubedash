# kubedash

kubedash provides a browser-based dashboard for viewing analytics from Kubernetes. It gives teams a single place to inspect Kubernetes data instead of working only with command-line output.

## Features

- Display Kubernetes analytics in a web dashboard.
- Run the dashboard as a JavaScript application.
- Open the dashboard from a browser after starting the application.

## Installation

Install kubedash with npm:

```bash
npm install kubedash
```

If you are working from a local checkout, install the project dependencies instead:

```bash
npm install
```

## Usage

Start kubedash with the default configuration:

```bash
npx kubedash
```

To run it on a specific port, pass the port option to the application:

```bash
npx kubedash --port 8080
```

Then open `http://localhost:8080` in a browser.

## License

kubedash is licensed under the Apache License 2.0 (Apache-2.0).

This project is based on [kubernetes-retired/kubedash](https://github.com/kubernetes-retired/kubedash). The original project and its copyright notices remain subject to the Apache-2.0 license.
