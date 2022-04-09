# Templates
 - Templates are written [handlebars style](https://handlebarsjs.com/guide/)
     - {{ variable }}
 - CSS and Javascript files can be linked following normal html syntax within the head block. 
     - {{#block head}}
'<link rel="stylesheet" href="styles/bootstrap.css">
<link rel="stylesheet" href="styles/decko.css">
<link rel="stylesheet" href="styles/project.css">
'<link rel="stylesheet" href="fontawesome/css/all.css">'
{{/block}}  
 - Noodles