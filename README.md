# inQom

End to end testing with [Playwright](https://playwright.dev/).

# Install

- `git clone git@github.com:juliendiotdervaux/inQom.git`
- `nvm install 18.13.0` or `nvm use 18.13.0`
- `yarn`

# Launch the tests

- To run all end-to-end tests :

`npx playwright test __tests__`
Every `*.spec.js` file in the `__tests__` directory'' is executed, the rest is ignored.
