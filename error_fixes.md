# Simple Error fixes

** 
When running “npm install”
 and you get an error that looks like this:
npm ERR! Unexpected token } in JSON at position 76128

you should try the following commands.
one of them would definitely work.

rm -f package-lock.json && npm install


rm -rf node_modules && npm install


rm -f package-lock.json && rm -rf node_modules && npm install

****

