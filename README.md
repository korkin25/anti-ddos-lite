# anti-ddos-lite
A short PHP app to block bots during DDoS attack.

## Description
Most of bots can't execute JavaScript code or can execute code partiraly. This app filters traffic from bots by using simple JavaScript code. So, bots will be denied to read original pages, they will be get only a single stop-page. As result DDoS attack will be reduced by elemenation of bots traffic that participating in the DDoS attack.

## How to use

Just include the code as first line in index.php.
```php
<?php
require "anti-ddos-lite/anti-ddos-lite.php";

//
// index.php code bellow
// ...
//

?>
```
