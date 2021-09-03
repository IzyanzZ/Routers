# Version

The Version Axonix/Router Is : 1.0.0dev

# Router

Routers Easy Routing Systems

# Usage

```
<?php

route("/", function() {
  return view("welcome");
})

$action = $_SERVER["REQUEST_URI];
dispatch($action);
```



# Installation

``` 
composer require axonix/router
```
