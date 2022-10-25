# Preparation and after any changes to package.json

Install node and then in root directory:

npm install

# Use with Editor
## Cursive
* run `npx shadow-cljs server` in IDE terminal
* use Clojure REPL → Remote Run Configuration to connect to the provided nREPL server.
  * Just select the "Use port from nREPL file" option

## Calva plug-in for Visual Studio Code

* Click on REPL at bottom of editor window.
* Click "Start your project with a REPL (aka Jack-in)" at the drop down that appears at the top of editor window."
* Select "shadow-cljs" project type.
* Select :hanami and press OK.
* You will see command "npx shadow-cljs -d cider/cider-nrepl:0.28.5 watch :hanami" run in the terminal window in the bottom pane of editor.
* Choose to connect to ":hanami" at the top.
* Open http://localhost:8700 in your browser.
* The REPL will then be connected to the javascript engine running the app in your browser.

## Cider on Emacs

* Similar to above?
