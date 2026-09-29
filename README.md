# React Learning Module

A small, browser-ready React example for the JavaScript React course. The page loads React 18, ReactDOM, and Babel from public CDNs and renders a live clock with a functional React component.

## Why this project is useful

This sample is intentionally compact so learners can focus on core React concepts without a build tool or package manager:

- Mounts a React application with `ReactDOM.createRoot`.
- Uses `React.useState` to store the current time.
- Uses `React.useEffect` to update the clock every second.
- Cleans up the interval when the component is unmounted.
- Runs directly in a modern browser from a single HTML file.

## Getting started

### Prerequisites

- A modern web browser with JavaScript enabled.
- Optional: a local static HTTP server for consistent browser behavior.

### Run the example

1. Clone the repository and enter the project directory:

   ```bash
   git clone https://github.com/VoidLance/course-files-javascript-react-reactsample2.git
   cd course-files-javascript-react-reactsample2
   ```

2. Open `index.html` in a browser.

   Alternatively, serve the directory locally:

   ```bash
   python3 -m http.server 8000
   ```

   Then visit <http://localhost:8000>.

The page displays **This is React Learning Module** followed by the current local time. The React and Babel scripts are loaded from the CDN URLs in `index.html`, so an internet connection is required when the page loads.

## Project structure

```text
.
├── index.html   # React example and browser entry point
└── README.md    # Project documentation
```

## Getting help

For React concepts, consult the [React documentation](https://react.dev/learn). For a project-specific question or suspected issue, [open a GitHub issue](https://github.com/VoidLance/course-files-javascript-react-reactsample2/issues) with a clear description and steps to reproduce it.

## Contributing

Contributions that improve the learning example or its documentation are welcome:

1. Fork the repository and create a focused branch.
2. Make your change in `index.html` or `README.md`.
3. Test the page in a current browser.
4. Open a pull request describing what changed and why.

Please keep examples beginner-friendly and avoid adding build tooling unless the project requirements change.

## Maintainer

This project is maintained by [VoidLance](https://github.com/VoidLance). Community contributions and constructive feedback are welcome.
