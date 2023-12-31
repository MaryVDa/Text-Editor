# Text Editor Starter Code

## Description
A text editor app that meets PWA criteria and can be used online or offline. 

## User Story
AS A developer   
I WANT to create notes or code snippets with or without an internet connection   
SO THAT I can reliably retrieve them for later use   

## Acceptance Criteria
GIVEN a text editor web application   
WHEN I open my application in my editor   
THEN I should see a client server folder structure   
WHEN I run `npm run start` from the root directory   
THEN I find that my application should start up the backend and serve the client   
WHEN I run the text editor application from my terminal   
THEN I find that my JavaScript files have been bundled using webpack    
WHEN I run my webpack plugins   
THEN I find that I have a generated HTML file, service worker, and a manifest file   
WHEN I use next-gen JavaScript in my application   
THEN I find that the text editor still functions in the browser without errors   
WHEN I open the text editor   
THEN I find that IndexedDB has immediately created a database storage   
WHEN I enter content and subsequently click off of the DOM window   
THEN I find that the content in the text editor has been saved with IndexedDB   
WHEN I reopen the text editor after closing it   
THEN I find that the content in the text editor has been retrieved from our IndexedDB   
WHEN I click on the Install button   
THEN I download my web application as an icon on my desktop   
WHEN I load my web application   
THEN I should have a registered service worker using workbox   
WHEN I register a service worker   
THEN I should have my static assets pre cached upon loading along with subsequent pages and static assets   
WHEN I deploy to Heroku   
THEN I should have proper build scripts for a webpack application   

## Installation
Install these packages:   
```npm i```
```npm i express```      
```npm i idb```
```npm i if-env```      
```npm i webpack```   
```npm i webpack-cli```   

## Usage
In the terminal enter ```npm run build```. Then enter ```npm run start``` to start the application.   
After starting the application go to your local host.

## Screenshot
![image](https://github.com/MaryVDa/Text-Editor/assets/122223756/e1673b89-d20e-4081-ba0b-0df4bf01cb27)

## Deployed App
Deployed using Heroku: https://text-editor-mvd-a2fa7061c883.herokuapp.com/

## GitHub
Contact for any questions:   
https://github.com/MaryVDa/Text-Editor

## Credits
Starter code by: https://github.com/coding-boot-camp/cautious-meme 
