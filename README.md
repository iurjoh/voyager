# Voyager

[Português (Brasil)](README.pt-BR.md) | **English**

A React front-end study project from the Code Institute Full Stack course period.

**Source:** public repository. Documentation reviewed on 2026-10-01.

## Status

Study project from the Code Institute Full Stack course period (last commits in 2023). The previous README was the unchanged Create React App template text; it was replaced by this document on 2026-10-01. The project is not currently deployed at a known public URL.

## Purpose

Voyager is a React front-end built on the course's "Moments" walkthrough template (the package name is still `moments`). The repository has no description and the intended product was not confirmed during this review; it appears to be a sibling or earlier attempt of the travel app [Voyage](https://github.com/iurjoh/voyage), but that relationship is unverified and is not asserted as fact. The matching API for projects of this stack is a Django REST Framework backend; this repository contains only the React front-end.

## Tech stack

From `package.json`:

- React 18 with `react-scripts` (Create React App) and React Router
- React Bootstrap and Bootstrap
- Axios for API calls, `jwt-decode` for token handling
- `react-infinite-scroll-component`, `react-toastify`
- Testing Library (jest-dom, react, user-event)

## Run locally

```bash
npm install
npm start
```

Opens on `http://localhost:3000`. A running backend API is needed for real data. Other scripts: `npm test`, `npm run build`. A `heroku-prebuild` script remains from the original Heroku deployment setup; no current deployment is verified.

## Development record

The exact feature set and original planning notes were not reconstructed during this documentation update, and no process history is invented here. Git history is the source for implementation details.

## Testing

Testing Library dependencies are present, but the test suite was not run in this update. Before any reuse, run `npm install` and `npm test` and check the app against a live backend.

## Credits and license status

Bootstrapped with Create React App and based on the Code Institute "Moments" walkthrough template. No `LICENSE` file was found at the repository root during this review; third-party template code retains its original terms, and this update does not apply a new license to them.
