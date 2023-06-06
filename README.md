# Dream App: Text2Image Generation using OpenAI's DALL-E API

I built a simple application that allows a user to enter a prompt and recieve back an illustration using DALLE Image Generation. 

## Implementation

On the frontend, we have a form that a user can submit. Then, it goes into a loading state while it sends an HTTP request to a backend server that I've built in Node.js. This server makes a request to OpenAI's DALL-E API, which returns an image url to display on the browser for the end-user. In the case that a 'bad-word' is entered in the prompt, which would normally break our server, I have added error handling that will notify the end-user.

## Stack

- Vite as a build tool for this application
- Node.js for building the backend server
- Express and CORS for handling requests on the backend
- OpenAI API for making requests to DALL-E image generation

## Results

<img width="962" alt="image" src="https://github.com/sriramanved/dream/assets/67165828/aac09d05-34b5-40b0-abc8-7e9197f5b1b8">


<img width="1293" alt="image" src="https://github.com/sriramanved/dream/assets/67165828/d426288e-e82d-4a57-8854-c8ad101a563a">

<img width="1304" alt="image" src="https://github.com/sriramanved/dream/assets/67165828/bcfa67a0-0dcf-4404-84b1-2aec667b2945">




