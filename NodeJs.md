
***Comands to NodeJS***

***Error - Maximum call stack size exceeded:***
 
 -> rm -rf node_modules
 -> npm cache clean --f
 -> npm install
 -> node --stack-size=16000 <file>
 -> ou ainda para o packjson:
 -> "scripts": {"setup": "node --stack-size=16000 index.js"}

***Message Error - "npm WARN config global `--global`, `--local` are deprecated. Use `--location=global` instead" :***

  -> Acessa folder of nodejs
  -> Edit the file npm.txt and find prefix -g and replace for: prefix --location=global
  -> Edit the file npm.cmd and find prefix -g and replace for: prefix --location=global
  
***Memory HEAP:***
  -> node_options= --max_old_space_size=4096 