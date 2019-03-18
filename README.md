# IoT Engineering
## Hands-on of lesson 5
For slides and example code, see [lesson 5](../../../fhnw-iot/blob/master/05/README.md)

> *Note: Do not work on this repository right away.*<br/>
> *[Create your personal copy by clicking this GitHub Classroom link](https://classroom.github.com/a/sLgnlWjp).*

### a) HRM BLE Peripheral, 15'
* Build and run the previous nRF52840 BLE example.
* Use the [.ino link](https://github.com/tamberg/fhnw-iot/blob/master/05/Arduino/nRF52840_HrmBlePeripheral/nRF52840_HrmBlePeripheral.ino) on the page to find the source code.
* Explore the HRM example using a smartphone app.
* Draw the HRM profile as a tree, with services, etc.

### b) Scanner BLE Central, 15'
* Build and run the previous nRF52840 BLE example.
* Use the [.ino link](https://github.com/tamberg/fhnw-iot/blob/master/05/Arduino/nRF52840_ScannerBleCentral/nRF52840_ScannerBleCentral.ino) on the page to find the source code.
* Add a checkReportForUuid() for the Battery Service.
* Can you spot the UUID in the advertising data?

### c) Beacons, 15'
* Build and run the previous nRF52840 BLE example.
* Use the [.ino link](https://github.com/tamberg/fhnw-iot/blob/master/05/Arduino/nRF52840_BeaconBleObservable/nRF52840_BeaconBleObservable.ino) on the page to find the source code.
* Test the beacon with a dedicated [iOS](https://itunes.apple.com/app/nrf-beacons/id879614768?mt=8)/[Android](https://play.google.com/store/apps/details?id=no.nordicsemi.android.nrfbeacon) app.
* Which information is transferred by a beacon?

### d) HomeKit, 15'
* [HomeKit](https://en.wikipedia.org/wiki/HomeKit) is a proprietary home-automation system.
* Try _File > Examples > Adafruit Bluefruit nRF52 > Projects > HomeKit > [homekit_lightbulb](https://github.com/adafruit/Adafruit_nRF52_Arduino/blob/master/libraries/Bluefruit52Lib/examples/Projects/homekit/homekit_lightbulb/homekit_lightbulb.ino)_
* An iOS device is required to test the Peripheral.
* Read the code, how is security implemented?

### Submitting results
* [Commit and push](#git) local changes to your repository.
* Want a review? [Create an issue](../../issues/new), mention me (@tamberg).

## Tools
### Git
On your computer
* In the hands-on repository [fork for your class](../../network/members), in README.md, click the _GitHub Classroom link_.
* Once you accept the assessment, you get a personal, private repository URL for your _USER_NAME_:<pre>
http://github.com/fhnw-iot-CLASS/fhnw-iot-work-05-USER_NAME</pre>

On your computer or Raspberry Pi
* Clone the repository<pre>
    $ cd ~
    $ git clone REPO_URL</pre>
* Add a file<pre>
    $ git add FILE</pre>
* Commit changes<pre>
    $ git commit FILE -m "Fixed all bugs"</pre>
* Push changes<pre>
    $ git push</pre>

## Wiki
- [IoT Engineering Wiki](https://github.com/tamberg/fhnw-iot/wiki)

## Support
- [IoT Engineering Slack](https://fhnw-iot.slack.com/)
