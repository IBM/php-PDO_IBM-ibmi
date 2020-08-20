# PDO_IBM

Interface for PHP to Db2 for i. This is a fork of the `PDO_IBM` nterface for PHP to Db2 for z/OS and LUW.

This code is only to be compiled and run on IBM i and offers no guaranteed compatibility with other platforms.

## Prerequisites

You will need PHP installed, as well as some key development tools:
```
yum install make-gnu gcc
```
To get started with IBM i RPMs, see http://ibm.biz/ibmi-rpms

## How to run sample program

### connect.php:-

```
<?php
        $db = null;
        $dsn = "ibm:<DSN NAME>";
        $user = "<USER>";
        $pass = "<PASSWORD>";

        $pdo = new PDO($dsn, $user, $pass);
        if ($pdo)
           print "Connection Successful.\n";

?>

```

To run the sample:- php connect.php

## Contributing:
See [CONTRIBUTING.md](CONTRIBUTING.md)
