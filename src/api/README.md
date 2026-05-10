# API Layer

This directory contains the mock API implementation for the application. Since there is no real backend, these functions simulate asynchronous network calls.

## Files
- **`mockApi.js`**: The core mock API. It uses `fetch` to read JSON files from `/public/data` and includes `setTimeout` to mimic network latency.

## Responsibilities
- Handling authentication requests.
- Fetching customer profiles.
- Fetching transaction data.
- Structured logging of all simulated "requests" and "responses".
