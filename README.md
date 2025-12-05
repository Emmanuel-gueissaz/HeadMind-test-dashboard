
## Installation and launch instructions 

`cd VULNERABILITY.GUI`

`npm install`

`npm run dev`

## Technologies used 

To set up this small application, I used the technologies that I used in my previous professional experience.

which is : 
The **VueJs** framework with the **Quasar** library and the language **TypeScript**.

## Time spent on the project

I spent between 4 and 5 hours 

## Explanation of technical choices

### Functional 

First, I didn’t really understand the incident part. We can create incidents, but they don’t appear in the mockups (because the screen is showing vulnerabilities instead)?

I added a profile selector in the top right corner so you can easily switch from a standard user to an admin (and culture).

Some parts are not 100% compliant, either because the framework is limiting in those areas (there might be options for overriding, but that would take more time), or because there are contrast issues (especially for statuses and severity levels).

### Technique 

We have several components with simple functionality that can be reused across the application.

For typing, I mainly use interfaces, but also types when appropriate.

The application includes stores that share a common state throughout the app. These stores are also where I implemented the saving mechanism.

For now, all data is saved in local storage. The frontend is structured to work with an API, but since no backend is connected yet, everything is stored locally (like a cache).

It is possible that you find quite a few "//eslint-disable*", it’s because es-lint considers the variable called in the template as "not used"

for finish I don't write in **HTML** but in **PUG** which I find more light


