# w_19_text_editor-PWA

## Project overview
``` This week we learned about Progreassive Web Application. PWA is A web-base application that can:
 * Works across different devices platforms.
 * Provides offline functionality, allowing users to access certain features or content even without an internet connection.
 * Utilizes service workers to cache and manage resources, enabling faster load times and performance.
 * Can be easily added to a user's home screen or app drawer for quick access.
 * Benefits from improved security, as it's served over HTTPS.

In summary PWAs aim to bridge the gap between web and native apps, delivering a more user-friendly and efficient experience for both developers and users.

```
## Project detais
```
In this project I've build text editor that runs in the browser but also can be downloaded to the computer an dthat run without internet.
```

## User Story

```md
AS A developer
I WANT to create notes or code snippets with or without an internet connection
SO THAT I can reliably retrieve them for later use
```

## Acceptance Criteria

```md
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
```

The following picture shows the web application's appearance:
