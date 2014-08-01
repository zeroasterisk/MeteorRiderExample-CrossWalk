# MeteorRider Example

**CrossWalk 8.37.185.0 arm**

This is a basic example demonstrating MeteorRider working within
[CrossWalk](https://crosswalk-project.org/#documentation/cordova/develop_an_application)

## Rebuild

Assuming you already have the basics you need for CrossWalk,
including the CrossWalk package downloaded and extracted.

```
$ cd /tmp
$ git clone https://github.com/zeroasterisk/MeteorRiderExample-CrossWalk.git MRExample
$ ~/crosswalk-cordova-8.37.185.0-arm/bin/create /tmp/MeteorRiderExampleCrosswalk.8.37.185.0.arm com.example.mr mr
$ cd MeteorRiderExampleCrosswalk.8.37.185.0.arm
$ cp ../MRExample/assets/www/js/meteor-rider.js assets/www/js/
$ cp ../MRExample/assets/www/js/app.js assets/www/js/
$ cp ../MRExample/assets/www/index.html assets/www/
$ ./cordova/run
```

Tested on an old Android Xoom on Ice Cream Sandwich... *Living large...*
