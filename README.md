# Temperature sensor tracker

## schema
```
+---------------+
|               |
| client device |
|               |
|               |
|               |
+---------------+
        |
        | API
        | JSON text over IP stream socket
        | 
        |
        |
       \/
+---------------+            +--------------------+
|               |            |                    |
| tesent.ml     |            | openweather        |
| * API north   |  IP API    | ambient temp data  |
| * RRD         +<-----------+                    |
| * WWW         |            |                    |
| * API south?  |            |                    |
+---------------+            +--------------------+




```


## process
* client device (custom sensor)
  * collect data
  * pushes it to TESENT via json text API
* tesent.ml
  * listen IP socket to collect custom sensor data
  * maintain database to store data
  * maintain web server with customer area
    * user register
    * custom sensor creation and authentication
    * current data graphs
  * maintain customer database
  * collect and store data from openweather
  * maintain API to android/ios software (maybe)
