# natours

> In the project, we implement the sass 7-1 architecture   

* _that means, there are partials sass file which adds up to make one css file for the site_   
* _to make partials file, we add new directories and the name of the partials start with underscore_ " _ "    
* _the 7 folders are-_   
  __abstracts__ - _code that doesn't produce output (variables, mixins , ... )_   
  __base__ - _all the base / default definition is written here_     
  __components__ - _files for each of the components_    
  __layout__ - _for global layout (header, footer, ... )_
  __pages__ - _styles for specific page_      
  __themes__ - _for any themes_      
  __vendors__ - _for third party inclusion(bootstrap, icons, ...)_     
  whereas in natours, we haven't used themes and vendor ...

* _then we have to import it to the main file_
