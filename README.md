# bootstrap4--coursera-assignments -- ALl
to run on local machine 
follow the steps  for linux--
1.open terminal 
2.paste the below code step by step  in your terminal

   1.  $ git clone https://github.com/shivam2003sy/bootstrap-coursera-assignments-.git
   2.  $ ls
   3.  $ cd bootstrap-coursera-assignments-/
4. install node and npm from : https://nodejs.org/en/download/
         before further steps make sure node and npm is working fine in your system 
         you can check this by using commands 
         
           $ node -v
           $ npm -v
                      
 if these command give some version means node is installed corectly you are good to go 
 
    
    5.  $ npm install
  (this will install required node modules )
    6.  $ npm start 
(This will start lite server output will be ):
[
 confusion@1.0.0 start /home/yadavshivam/Desktop/bootstrap-coursera-assignments-
> npm run lite


> confusion@1.0.0 lite /home/yadavshivam/Desktop/bootstrap-coursera-assignments-
> lite-server

Did not detect a `bs-config.json` or `bs-config.js` override file. Using lite-server defaults...
** browser-sync config **
{ injectChanges: false,
  files: [ './**/*.{html,htm,css,js}' ],
  watchOptions: { ignored: 'node_modules' },
  server: { baseDir: './', middleware: [ [Function], [Function] ] } }
[Browsersync] Access URLs:
 ---------------------------------------
       Local: http://localhost:3000
    External: http://192.168.42.225:3000
 ---------------------------------------
          UI: http://localhost:3001
 UI External: http://localhost:3001
 ---------------------------------------
[Browsersync] Serving files from: ./
[Browsersync] Watching files...
                                  ]
  that means you have sucessfully run this in your local machine and you will se this in browser

  

