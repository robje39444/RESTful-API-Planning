# RESTful-API-Planning
Planning a RESTful API with Fetch GET

I. API Selection – The public API that I chose is Healthcare.gov in the Health category. It is suitable for this assignment because it doesn't require an APIkey and uses the basic GET/POST endpoints with Requests sent over the web with HTTP and Returns JSON. The purpose is to provide information about the Health Insurance Marketplace in machine-readable formats so that innovators, entrepreneurs, and partners can turn it into new products and services. The Goal of this, for my purposes, would be to have a link for this in MyChart for patients to learn more about their options if they are uninsured or just want more information. 

II. Endpoint Mapping – The RESTful endpoints that will be used are 
/api/content -  The HTTP Method used is GET > To fetch a specific article or list of pages > Accepts query parameters > Returns JSON
                The HTTP Method POST > Create new content > JSON body with content data > Return new content with a unique ID
                
/api/glossary - The HTTP Method GET > Retrieve all terms or a specific definition > RETURNS glossary terms and definitions
                The HTTP Method POST > Add a new term to the glossary >	JSON body containing the term and its definition > RETURNS glossary entry with its generated ID.

/api/index -    The HTTP Method Get > Fetch a directory or search index >	Optional filtering or sorting query parameters >	RETURNS A structured map, list of links, or categorized index tree

III. Data Flow Diagram (textual) – The client will use JavaScript code that uses the popular JQuery library to request the information from a webpage. It supports JSON requests. Frontend frameworks will use a state machine pattern. A skeleton loader will be used to help with visuals with the text and title. If an error occurs such as 500, have a retry option, and a back to home button if a 404 error not found occurs. For conditional styling logic, have a publish status to warn admins it isnt public.  

IV. Form Handling – It will use CRUD operations (Create, Read, Update, Delete) using text inputs. It will use client-side validation rules such as the Title requiring a certain range of characters, the Body must not be empty, and the category must match. Will use Schemas to transform data into JSON with the use of Strings and Triggers. 

V. Technology Stack – Some Frontend frameworks that will be used is Zod or Yup. End to End (E2E) testing will be used for full stack validation.

VI. Implementation Steps – This project will take 3 months for completion. We will start with the build phase based on the project intake form. We will have a kickoff meeting to discuss the estimated amount of time needed in hours to complete each build. The build and network integration will be 6 weeks. We will have 3 weeks of integrated testing in the virtual environment. During this time we will also test the Mychart application to ensure the link to Healthcare.gov established connection. We will schedule 1 week for End to End testing in the production environment. We will have 3 Days for a Dry Run. At the end of that week we will have a final Go/No-Go meeting to begin Go-live the following week. We will bring the production system down at 2am the day of Go-live to migrate the build into production (1 hour downtime), and we will have a command center setup the first week to monitor any issues for quick resolution.
