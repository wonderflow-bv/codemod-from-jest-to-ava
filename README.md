# codemod-from-jest-to-ava

Codemod to convert tests written in jest to ava.

Check `fixtures/` folder to see which type of tests are supported.

## Usage

### Run a single codemod

`jscodeshift -t lib/mege-describes-into-its.js ./fixtures/simple-test-1-input.js -d -p`

### Test conversion

`npm t`
