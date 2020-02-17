# api-request-json

## Installer

``` javascript
yarn add api - request - json

or

npm i - S api - request - json
```

## Used

``` javascript 

import { GET, POST, PUT, DELETE } from 'api-request-json'; 



    POST('url',data);

    PUT('url/{id}',data);

    GET('url').then(data => {

            console.log(data);
            
    });

    DELETE('url/{id}');

}

```

