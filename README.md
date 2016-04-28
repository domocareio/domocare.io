# General

## Prerequisites


## Stream structure
### For the sensor
```
domosafety
├── <location>
│   ├── <device type>
│   │   ├── <sensor id>
│   │   │   ├── Battery Level
│   │   │   ├── time delta
│   │   │   ├── LQI
│   │   │   ├── RSSI
│   │   ├── <base unit id>
│   │   │   ├── Battery Level
│   │   │   ├── time delta
```

## Troubleshooting
Use [Google Chrome](https://www.google.com/chrome/) with the extention [JSONView](https://chrome.google.com/webstore/detail/jsonview/chklaanhfefbnpoihckbnefhakgolnmc) to test the request and have a formatted display of the server response.

# Getting started
## Authentication
You need the authorization token for the user you whish to access the data.

## Get streams list
```
https://<user id>.domocare.io/streams?auth=<authentication token>
```

## Get values for a stream
## Get values for a stream for a period
## Get all the value


# Examples
## Streams list
```json
[
   {
      "clientData":{
         "pryv-browser:bgColor":"#1abc9c"
      },
      "created":1457097846.206,
      "createdBy":"cil9kktap0029r061oabmlipb",
      "modified":1457097994.298,
      "modifiedBy":"cil9kktap0029r061oabmlipb",
      "name":"Diary",
      "parentId":null,
      "id":"diary",
      "children":[

      ]
   },
   {
      "clientData":{
         "pryv-browser:bgColor":"#2ecc71"
      },
      "created":1461588758.139,
      "createdBy":"cilnnsgcp04ayr0619cccgefi",
      "modified":1461589371.178,
      "modifiedBy":"cil9kktap0029r061oabmlipb",
      "name":"DomoSafety",
      "parentId":null,
      "id":"domosafety",
      "children":[
         {
            "name":"entrance",
            "parentId":"domosafety",
            "created":1461588778.226,
            "createdBy":"cilnnsgcp04ayr0619cccgefi",
            "modified":1461588778.226,
            "modifiedBy":"cilnnsgcp04ayr0619cccgefi",
            "id":"position-entrance",
            "children":[
               {
                  "name":"activity",
                  "parentId":"position-entrance",
                  "created":1461588778.231,
                  "createdBy":"cilnnsgcp04ayr0619cccgefi",
                  "modified":1461588778.231,
                  "modifiedBy":"cilnnsgcp04ayr0619cccgefi",
                  "id":"position-entrance-type-activity",
                  "children":[
                     {
                        "name":"163287-D",
                        "parentId":"position-entrance-type-activity",
                        "created":1461588778.235,
                        "createdBy":"cilnnsgcp04ayr0619cccgefi",
                        "modified":1461588778.235,
                        "modifiedBy":"cilnnsgcp04ayr0619cccgefi",
                        "id":"dbuid-163287-D",
                        "children":[
                           {
                              "clientData":{
                                 "pryv-browser:charts":{
                                    "electromotive-force/v":{
                                       "settings":{
                                          "color":"#1abc9c",
                                          "style":"spline",
                                          "transform":"none",
                                          "interval":"auto"
                                       }
                                    }
                                 }
                              },
                              "created":1461588778.244,
                              "createdBy":"cilnnsgcp04ayr0619cccgefi",
                              "modified":1461600335.645,
                              "modifiedBy":"cil9kktap0029r061oabmlipb",
                              "name":"Battery Level",
                              "parentId":"dbuid-163287-D",
                              "id":"dbuid-163287-D-batteryLevel",
                              "children":[

                              ]
                           },
                           {
                              "name":"LQI",
                              "parentId":"dbuid-163287-D",
                              "created":1461588778.253,
                              "createdBy":"cilnnsgcp04ayr0619cccgefi",
                              "modified":1461588778.253,
                              "modifiedBy":"cilnnsgcp04ayr0619cccgefi",
                              "id":"dbuid-163287-D-lqi",
                              "children":[

                              ]
                           },
                           {
                              "name":"RSSI",
                              "parentId":"dbuid-163287-D",
                              "created":1461588778.248,
                              "createdBy":"cilnnsgcp04ayr0619cccgefi",
                              "modified":1461588778.248,
                              "modifiedBy":"cilnnsgcp04ayr0619cccgefi",
                              "id":"dbuid-163287-D-rssi",
                              "children":[

                              ]
                           },
                           {
                              "clientData":{
                                 "pryv-browser:charts":{
                                    "time/s":{
                                       "settings":{
                                          "color":"#2980b9",
                                          "style":"spline",
                                          "transform":"none",
                                          "interval":"auto"
                                       }
                                    }
                                 }
                              },
                              "created":1461588778.24,
                              "createdBy":"cilnnsgcp04ayr0619cccgefi",
                              "modified":1461600416.273,
                              "modifiedBy":"cil9kktap0029r061oabmlipb",
                              "name":"time delta",
                              "parentId":"dbuid-163287-D",
                              "id":"dbuid-163287-D-time-delta",
                              "children":[

                              ]
                           }
                        ]
                     }
                  ]
               },
               {
                  "name":"base unit",
                  "parentId":"position-entrance",
                  "created":1461591735.369,
                  "createdBy":"cilnnsgcp04ayr0619cccgefi",
                  "modified":1461591735.369,
                  "modifiedBy":"cilnnsgcp04ayr0619cccgefi",
                  "id":"position-entrance-type-base_unit",
                  "children":[
                     {
                        "name":"163274-D",
                        "parentId":"position-entrance-type-base_unit",
                        "created":1461591735.374,
                        "createdBy":"cilnnsgcp04ayr0619cccgefi",
                        "modified":1461591735.374,
                        "modifiedBy":"cilnnsgcp04ayr0619cccgefi",
                        "id":"dbuid-163274-D",
                        "children":[
                           {
                              "clientData":{
                                 "pryv-browser:charts":{
                                    "electromotive-force/v":{
                                       "settings":{
                                          "color":"#34495e",
                                          "style":"spline",
                                          "transform":"none",
                                          "interval":"auto"
                                       }
                                    }
                                 }
                              },
                              "created":1461591735.385,
                              "createdBy":"cilnnsgcp04ayr0619cccgefi",
                              "modified":1461600422.763,
                              "modifiedBy":"cil9kktap0029r061oabmlipb",
                              "name":"Battery Level",
                              "parentId":"dbuid-163274-D",
                              "id":"dbuid-163274-D-batteryLevel",
                              "children":[

                              ]
                           },
                           {
                              "clientData":{
                                 "pryv-browser:charts":{
                                    "time/s":{
                                       "settings":{
                                          "color":"#2ecc71",
                                          "style":"spline",
                                          "transform":"none",
                                          "interval":"auto"
                                       }
                                    }
                                 }
                              },
                              "created":1461591735.379,
                              "createdBy":"cilnnsgcp04ayr0619cccgefi",
                              "modified":1461600395.488,
                              "modifiedBy":"cil9kktap0029r061oabmlipb",
                              "name":"time delta",
                              "parentId":"dbuid-163274-D",
                              "id":"dbuid-163274-D-time-delta",
                              "children":[

                              ]
                           }
                        ]
                     }
                  ]
               },
               {
                  "name":"door",
                  "parentId":"position-entrance",
                  "created":1461592441.029,
                  "createdBy":"cilnnsgcp04ayr0619cccgefi",
                  "modified":1461592441.029,
                  "modifiedBy":"cilnnsgcp04ayr0619cccgefi",
                  "id":"position-entrance-type-door",
                  "children":[
                     {
                        "name":"163292-D",
                        "parentId":"position-entrance-type-door",
                        "created":1461592441.036,
                        "createdBy":"cilnnsgcp04ayr0619cccgefi",
                        "modified":1461592441.036,
                        "modifiedBy":"cilnnsgcp04ayr0619cccgefi",
                        "id":"dbuid-163292-D",
                        "children":[
                           {
                              "clientData":{
                                 "pryv-browser:charts":{
                                    "electromotive-force/v":{
                                       "settings":{
                                          "color":"#f1c40f",
                                          "style":"spline",
                                          "transform":"none",
                                          "interval":"auto"
                                       }
                                    }
                                 }
                              },
                              "created":1461599332.143,
                              "createdBy":"cilnnsgcp04ayr0619cccgefi",
                              "modified":1461600428.322,
                              "modifiedBy":"cil9kktap0029r061oabmlipb",
                              "name":"Battery Level",
                              "parentId":"dbuid-163292-D",
                              "id":"dbuid-163292-D-batteryLevel",
                              "children":[

                              ]
                           },
                           {
                              "name":"LQI",
                              "parentId":"dbuid-163292-D",
                              "created":1461592441.053,
                              "createdBy":"cilnnsgcp04ayr0619cccgefi",
                              "modified":1461592441.053,
                              "modifiedBy":"cilnnsgcp04ayr0619cccgefi",
                              "id":"dbuid-163292-D-lqi",
                              "children":[

                              ]
                           },
                           {
                              "name":"RSSI",
                              "parentId":"dbuid-163292-D",
                              "created":1461592441.047,
                              "createdBy":"cilnnsgcp04ayr0619cccgefi",
                              "modified":1461592441.047,
                              "modifiedBy":"cilnnsgcp04ayr0619cccgefi",
                              "id":"dbuid-163292-D-rssi",
                              "children":[

                              ]
                           },
                           {
                              "clientData":{
                                 "pryv-browser:charts":{
                                    "time/s":{
                                       "settings":{
                                          "color":"#7f8c8d",
                                          "style":"spline",
                                          "transform":"none",
                                          "interval":"auto"
                                       }
                                    }
                                 }
                              },
                              "created":1461592441.041,
                              "createdBy":"cilnnsgcp04ayr0619cccgefi",
                              "modified":1461600450.374,
                              "modifiedBy":"cil9kktap0029r061oabmlipb",
                              "name":"time delta",
                              "parentId":"dbuid-163292-D",
                              "id":"dbuid-163292-D-time-delta",
                              "children":[

                              ]
                           }
                        ]
                     }
                  ]
               }
            ]
         },
         {
            "name":"living room",
            "parentId":"domosafety",
            "created":1461589017.131,
            "createdBy":"cilnnsgcp04ayr0619cccgefi",
            "modified":1461589017.131,
            "modifiedBy":"cilnnsgcp04ayr0619cccgefi",
            "id":"position-living_room",
            "children":[
               {
                  "name":"activity",
                  "parentId":"position-living_room",
                  "created":1461589017.135,
                  "createdBy":"cilnnsgcp04ayr0619cccgefi",
                  "modified":1461589017.135,
                  "modifiedBy":"cilnnsgcp04ayr0619cccgefi",
                  "id":"position-living_room-type-activity",
                  "children":[
                     {
                        "name":"163288-D",
                        "parentId":"position-living_room-type-activity",
                        "created":1461589017.139,
                        "createdBy":"cilnnsgcp04ayr0619cccgefi",
                        "modified":1461589017.139,
                        "modifiedBy":"cilnnsgcp04ayr0619cccgefi",
                        "id":"dbuid-163288-D",
                        "children":[
                           {
                              "clientData":{
                                 "pryv-browser:charts":{
                                    "electromotive-force/v":{
                                       "settings":{
                                          "color":"#1abc9c",
                                          "style":"spline"
                                       }
                                    }
                                 }
                              },
                              "created":1461589017.147,
                              "createdBy":"cilnnsgcp04ayr0619cccgefi",
                              "modified":1461591306.178,
                              "modifiedBy":"cil9kktap0029r061oabmlipb",
                              "name":"Battery Level",
                              "parentId":"dbuid-163288-D",
                              "id":"dbuid-163288-D-batteryLevel",
                              "children":[

                              ]
                           },
                           {
                              "name":"LQI",
                              "parentId":"dbuid-163288-D",
                              "created":1461589017.167,
                              "createdBy":"cilnnsgcp04ayr0619cccgefi",
                              "modified":1461589017.167,
                              "modifiedBy":"cilnnsgcp04ayr0619cccgefi",
                              "id":"dbuid-163288-D-lqi",
                              "children":[

                              ]
                           },
                           {
                              "name":"RSSI",
                              "parentId":"dbuid-163288-D",
                              "created":1461589017.152,
                              "createdBy":"cilnnsgcp04ayr0619cccgefi",
                              "modified":1461589017.152,
                              "modifiedBy":"cilnnsgcp04ayr0619cccgefi",
                              "id":"dbuid-163288-D-rssi",
                              "children":[

                              ]
                           },
                           {
                              "clientData":{
                                 "pryv-browser:charts":{
                                    "time/s":{
                                       "settings":{
                                          "color":"#bdc3c7",
                                          "style":"spline",
                                          "transform":"none",
                                          "interval":"auto"
                                       }
                                    }
                                 }
                              },
                              "created":1461589017.143,
                              "createdBy":"cilnnsgcp04ayr0619cccgefi",
                              "modified":1461600445.067,
                              "modifiedBy":"cil9kktap0029r061oabmlipb",
                              "name":"time delta",
                              "parentId":"dbuid-163288-D",
                              "id":"dbuid-163288-D-time-delta",
                              "children":[

                              ]
                           }
                        ]
                     }
                  ]
               }
            ]
         },
         {
            "name":"not applicable",
            "parentId":"domosafety",
            "created":1461591405.628,
            "createdBy":"cilnnsgcp04ayr0619cccgefi",
            "modified":1461591405.628,
            "modifiedBy":"cilnnsgcp04ayr0619cccgefi",
            "id":"position-not_applicable",
            "children":[
               {
                  "name":"help wristwatch",
                  "parentId":"position-not_applicable",
                  "created":1461591405.633,
                  "createdBy":"cilnnsgcp04ayr0619cccgefi",
                  "modified":1461591405.633,
                  "modifiedBy":"cilnnsgcp04ayr0619cccgefi",
                  "id":"position-not_applicable-type-help_wristwatch",
                  "children":[
                     {
                        "name":"163291-D",
                        "parentId":"position-not_applicable-type-help_wristwatch",
                        "created":1461591405.637,
                        "createdBy":"cilnnsgcp04ayr0619cccgefi",
                        "modified":1461591405.637,
                        "modifiedBy":"cilnnsgcp04ayr0619cccgefi",
                        "id":"dbuid-163291-D",
                        "children":[
                           {
                              "clientData":{
                                 "pryv-browser:charts":{
                                    "electromotive-force/v":{
                                       "settings":{
                                          "color":"#c0392b",
                                          "style":"spline",
                                          "transform":"none",
                                          "interval":"auto"
                                       }
                                    }
                                 }
                              },
                              "created":1461591405.647,
                              "createdBy":"cilnnsgcp04ayr0619cccgefi",
                              "modified":1461600439.173,
                              "modifiedBy":"cil9kktap0029r061oabmlipb",
                              "name":"Battery Level",
                              "parentId":"dbuid-163291-D",
                              "id":"dbuid-163291-D-batteryLevel",
                              "children":[

                              ]
                           },
                           {
                              "name":"LQI",
                              "parentId":"dbuid-163291-D",
                              "created":1461591405.657,
                              "createdBy":"cilnnsgcp04ayr0619cccgefi",
                              "modified":1461591405.657,
                              "modifiedBy":"cilnnsgcp04ayr0619cccgefi",
                              "id":"dbuid-163291-D-lqi",
                              "children":[

                              ]
                           },
                           {
                              "name":"RSSI",
                              "parentId":"dbuid-163291-D",
                              "created":1461591405.652,
                              "createdBy":"cilnnsgcp04ayr0619cccgefi",
                              "modified":1461591405.652,
                              "modifiedBy":"cilnnsgcp04ayr0619cccgefi",
                              "id":"dbuid-163291-D-rssi",
                              "children":[

                              ]
                           },
                           {
                              "clientData":{
                                 "pryv-browser:charts":{
                                    "time/s":{
                                       "settings":{
                                          "color":"#e67e22",
                                          "style":"spline",
                                          "transform":"none",
                                          "interval":"auto"
                                       }
                                    }
                                 }
                              },
                              "created":1461591405.642,
                              "createdBy":"cilnnsgcp04ayr0619cccgefi",
                              "modified":1461600433.72,
                              "modifiedBy":"cil9kktap0029r061oabmlipb",
                              "name":"time delta",
                              "parentId":"dbuid-163291-D",
                              "id":"dbuid-163291-D-time-delta",
                              "children":[

                              ]
                           }
                        ]
                     }
                  ]
               }
            ]
         },
         {
            "name":"toilet",
            "parentId":"domosafety",
            "created":1461588758.143,
            "createdBy":"cilnnsgcp04ayr0619cccgefi",
            "modified":1461588758.143,
            "modifiedBy":"cilnnsgcp04ayr0619cccgefi",
            "id":"position-toilet",
            "children":[
               {
                  "name":"activity",
                  "parentId":"position-toilet",
                  "created":1461588758.148,
                  "createdBy":"cilnnsgcp04ayr0619cccgefi",
                  "modified":1461588758.148,
                  "modifiedBy":"cilnnsgcp04ayr0619cccgefi",
                  "id":"position-toilet-type-activity",
                  "children":[
                     {
                        "name":"163286-D",
                        "parentId":"position-toilet-type-activity",
                        "created":1461588758.152,
                        "createdBy":"cilnnsgcp04ayr0619cccgefi",
                        "modified":1461588758.152,
                        "modifiedBy":"cilnnsgcp04ayr0619cccgefi",
                        "id":"dbuid-163286-D",
                        "children":[
                           {
                              "clientData":{
                                 "pryv-browser:charts":{
                                    "electromotive-force/v":{
                                       "settings":{
                                          "color":"#27ae60",
                                          "style":"spline",
                                          "transform":"none",
                                          "interval":"auto"
                                       }
                                    }
                                 }
                              },
                              "created":1461588758.161,
                              "createdBy":"cilnnsgcp04ayr0619cccgefi",
                              "modified":1461600409.618,
                              "modifiedBy":"cil9kktap0029r061oabmlipb",
                              "name":"Battery Level",
                              "parentId":"dbuid-163286-D",
                              "id":"dbuid-163286-D-batteryLevel",
                              "children":[

                              ]
                           },
                           {
                              "name":"LQI",
                              "parentId":"dbuid-163286-D",
                              "created":1461588758.17,
                              "createdBy":"cilnnsgcp04ayr0619cccgefi",
                              "modified":1461588758.17,
                              "modifiedBy":"cilnnsgcp04ayr0619cccgefi",
                              "id":"dbuid-163286-D-lqi",
                              "children":[

                              ]
                           },
                           {
                              "name":"RSSI",
                              "parentId":"dbuid-163286-D",
                              "created":1461588758.165,
                              "createdBy":"cilnnsgcp04ayr0619cccgefi",
                              "modified":1461588758.165,
                              "modifiedBy":"cilnnsgcp04ayr0619cccgefi",
                              "id":"dbuid-163286-D-rssi",
                              "children":[

                              ]
                           },
                           {
                              "clientData":{
                                 "pryv-browser:charts":{
                                    "time/s":{
                                       "settings":{
                                          "color":"#16a085",
                                          "style":"spline",
                                          "transform":"none",
                                          "interval":"auto"
                                       }
                                    }
                                 }
                              },
                              "created":1461588758.156,
                              "createdBy":"cilnnsgcp04ayr0619cccgefi",
                              "modified":1461600404.212,
                              "modifiedBy":"cil9kktap0029r061oabmlipb",
                              "name":"time delta",
                              "parentId":"dbuid-163286-D",
                              "id":"dbuid-163286-D-time-delta",
                              "children":[

                              ]
                           }
                        ]
                     }
                  ]
               }
            ]
         }
      ]
   },
   {
      "clientData":{
         "pryv-browser:bgColor":"#3498db"
      },
      "created":1461751760.031,
      "createdBy":"cilxjawpa0bhar0616wy9vorf",
      "modified":1461760669.566,
      "modifiedBy":"cilxjawpa0bhar0616wy9vorf",
      "name":"Test",
      "parentId":null,
      "id":"test",
      "children":[

      ]
   }
]
```
