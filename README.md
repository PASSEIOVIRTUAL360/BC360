# BC360 Virtual Tour

This project contains a 360º tour of Balneário Camboriú. The contents were generated with a tour creator tool and require a simple HTTP server to run.

## Running the tour locally

1. Install a static server such as [`http-server`](https://www.npmjs.com/package/http-server):

   ```bash
   npx http-server
   ```

2. Start the server in the repository directory and open `index.htm` in your browser.

The page automatically selects a script optimized for desktop or mobile depending on the screen width. Devices with width greater than 800px will now load the desktop experience by default.
