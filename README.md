Bootstrap hidden/visible Extension
==================================

Extends and improves the Bootstrap 2.3.2 functionality to hide an display content depending on device, using css classes.

These classes revamps the default bootstrap classes using device detection instead of just width and height detection. This means that you will not see any effect other than on the specific devices, no matter how you resize your desktop browser it's still detected as *desktop*


| Class         | Phones portrait | Phones landscape  | Tablets portrait | Tablets landscape  | Desktop |
| ------------- |:---------------:| -----------------:|-----------------:|-------------------:|--------:|
| `.hidden-phone-landscape`   | **Visible** | Hidden  | **Visible**  | **Visible**  | **Visible**  |
| `.visible-phone-landscape`  | Hidden  | **Visible**  | Hidden  | Hidden  | Hidden  |
| `.hidden-phone-portrait`    | Hidden  | **Visible**  | **Visible**  | **Visible**  | Hidden  |
| `.visible-phone-portrait`   | **Visible** | Hidden  | Hidden  | Hidden  | **Visible**  |
| `.visible-phone`            | **Visible** | **Visible**  | Hidden  | Hidden  | Hidden  |
| `.hidden-phone`             | Hidden  | Hidden  | **Visible**  | **Visible**  | **Visible**  |
| `.hidden-tablet-landscape` | **Visible**  | **Visible**  | **Visible**  | Hidden  | **Visible**  |
| `.visible-tablet-landscape` | Hidden  | Hidden  | Hidden  | **Visible**  | Hidden  |
| `.hidden-tablet-portrait`   | **Visible**  | **Visible**  | Hidden  | **Visible**  | **Visible**  |
| `.visible-tablet-portrait`  | Hidden  | Hidden  | **Visible**  | Hidden  | Hidden  |
| `.hidden-tablet`             | **Visible**  | **Visible**  | Hidden  | Hidden  | **Visible**  |
| `.hidden-desktop`           | **Visible**  | **Visible**  | **Visible**  | **Visible**  | Hidden  |
| `.visible-desktop`          | Hidden  | Hidden  | Hidden  | Hidden  | **Visible**  |


## Change log

### Version 1.0
* First release. Tested and *should* work as expected.
