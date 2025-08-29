# Node.js CI/CD with GitHub Actions

## Workflow

- **Trigger:** Runs automatically on every `push` to the repository.
- **Steps:**
  1. Checkout the code
  2. Set up Node.js v22.18.0
  3. Install project dependencies (`npm install`)
  4. Run tests (`npm test`)
  5. Mock deployment step (`echo "Deploying..."`)

## Deliverables

- GitHub Actions workflow is defined in `.github/workflows/sample-ci.yml`.
- This pipeline makes sure that the code can be built and tested in a clean environment before "deployment".

## Reference

👉 [Building and testing Node.js with GitHub Actions](https://docs.github.com/en/actions/tutorials/build-and-test-code/nodejs)