Install Pleeease

 npm install -g pleeease-cli

create a configration file .pleeeaserc  
{
  "in": ["*.css", "*.scss"],
  "out": "production.min.css",
  "rem":true,
  "sass": true,
  "minifier": false,
  "browsers": ["last 6 versions"]
}

Compile with the following command
pleeease compile

watch command
pleeease watch


Referance url : http://pleeease.io/
