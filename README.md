# RESTful-API-Planning
Planning a RESTful API with Fetch GET

I. API Selection – The public API that I chose is Healthcare.gov in the Health category. It is suitable for this assignment because it doesn't require an APIkey and uses the basic GET/POST endpoints with Requests sent over the web with HTTP and Returns JSON. The purpose is to provide information about the Health Insurance Marketplace in machine-readable formats so that innovators, entrepreneurs, and partners can turn it into new products and services. The Goal of this, for my purposes, would be to have a link for this in MyChart for patients to learn more about their options if they are uninsured or just want more information. 

II. Endpoint Mapping – The RESTful endpoints that will be used are /api/content, /api/glossary, /api/index for example. With adding .json at the end get and return JSON for the POST.  Describe how each maps to HTTP verbs (GET, POST, etc.) and what data they return or accept.

III. Data Flow Diagram (textual) – explain how your client will fetch data from the public API, process it, and render it in the UI. Mention loading states, error handling, and conditional styling logic.

IV. Form Handling – detail any form controls you will implement, the validation rules applied locally, and how the collected data is transformed into a JSON payload for submission to your Python backend (you do not need to build the backend, only outline the contract).

V. Technology Stack – list the front end libraries/frameworks (e.g., Flask), and any tools you will use for testing.

VI. Implementation Steps – a chronological plan: set up project progression → implement fetch GET with loading/error states → render dynamic lists/tables → add form controls & validation → integrate conditional styling → final review and documentation.
