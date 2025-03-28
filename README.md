<img src="https://github.com/user-attachments/assets/9dc321d3-d912-4897-b1f8-f8c6634d9a24" >
<img width="1417" alt="Screenshot 2025-03-28 at 3 34 20 PM" src="https://github.com/user-attachments/assets/30537373-c23f-4a1b-ba62-47c887a0a9a1" />
<img width="1415" alt="Screenshot 2025-03-28 at 3 33 47 PM" src="https://github.com/user-attachments/assets/51dd5739-691a-4225-96ad-8b30d347fb7f" />

# aedp-frontend
https://aedpinstitute.org

## Run locally

Run the development server:

```bash
$ npm run dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see local site.


## Storybook

Storybook is set up so we can work on components outsidre app context. Toe of the enti run it simply use:

```bash
$ npm run storybook
```

## Code Formatting and Linting

Ensure your code adheres to the project's style guidelines by using the following commands:

### Check for Linting Issues

To identify any formatting or linting issues in the codebase:

```bash
npm run lint
```

### Automatically Fix Linting Issues

To fix most of the identified issues automatically:

```bash
npm run lint:fix
```

For issues that require manual attention, review the output of the lint command and make necessary adjustments.


## Backend mocks

An OpenAPI specification is available in the `openapi` folder. A package manifest is also available to enable running a mock server easily which can be used for connecting APIs without an active backend.

To start the mock server, install dependencies in that folder and start it:

```bash
$ cd openapi
$ npm install
$ npm start
```

You can also start the mock server yourself if you wish to change execution flags:

```bash
$ npx prism mock -p 8000 ./spec.yaml
```

Available endpoints may change in the future. Check out the list of them when the mock server is started.
