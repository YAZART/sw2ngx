![sw2ngx logo](https://raw.githubusercontent.com/YAZART/sw2ngx/master/sw2ngx.png)

Generate Angular 5 API module from swagger.json

##  1. install

```
    npm install -g sw2ngx
```

## 2. run

```
    sw2ngx -c ./path/to/swagger.json -o ./path/to/api/module/folder
```

OR

```
    // for example
    sw2ngx -c https://petstore.swagger.io/v2/swagger.json -o ./path/to/api/module/folder
```
## 3. last features

 1. migrate to tipescript
 2. URL config load
 3. bin directory
 4. [WIP] config to merge

 ## 3.1 Experimental functionality

If there are api that are not generated by the swagger, then it is possible to describe the objects to be generated in a separate file. It should be in the folder where the application is launched and its name should be: `sw2ngx-extend.json`. An example file is given in `example-sw2ngx-extend.json`; In the future, its structure will be simplified.