# Tracepoint — API & Webhook Workbench

A client-side API debugging and webhook inspection portfolio demo built with HTML, CSS, and vanilla JavaScript.

## Features
- HTTP request builder for GET/POST/PUT/PATCH/DELETE
- Query parameters, request headers, and JSON body
- Live fetch requests to public endpoints (browser CORS policies apply)
- Response status, timing, response body, JSON formatting, copy response
- cURL generation and fetch snippet generation
- Browser-local request history and CSV export
- JSON formatter/validator and webhook payload structure inspector

## Run locally
Open `index.html` in a modern browser. No build step or package install required.

## Important limitations
This is a front-end portfolio demo, not a production API gateway. Requests are made from the user's browser. Target servers must allow CORS. Do not paste private API keys or production secrets into the demo. History is stored in browser localStorage. The webhook inspector analyzes sample JSON locally; no webhook receiver or backend is deployed.
