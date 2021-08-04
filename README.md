# Implementing Redux

You'll be building a clone of Redux -- in this case, dedux -- in the service of a simple counter app.

## Install dependencies

```bash
> yarn
```

## Run the tests

Start the tests with:

```bash
> yarn test --watch
```

Read through the [test cases](implementing-redux/__tests__/tests.spec.js) and implement the required logic in `implementing-redux/index.js`

## Wire it all up

From the root of the project run

```bash
> npx serve
```

Then go to `http://localhost:5000/implementing-redux/counter` in your address bar. In the file `implementing-redux/counter.js`, see if you can do the following:

- hook up your implementation of Dedux to the elements in `counter.html`
- have the counter reflect a value stored in your Dedux state
- when the up button is pushed, the counter should increase
- when the down button is pushed, the counter should decrease
- when the reset button is pushed, the counter should reset to zero
- **Bonus**: add a middleware to your store which will persist the latest count to localstorage and set up your initial state to use this value
