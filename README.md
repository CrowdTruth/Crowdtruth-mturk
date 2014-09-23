Crowdtruth-mturk
================

Extension for the CrowdWatson framework that adds Amazon Mechanical Turk as a platform.

Notice that you must configure the package to provide the API key for your AMT account. In order to configure the package, it is necessary to create your own configuration using the following command:

```
    $ php artisan config:publish crowdtruth/mturk
```

Afterwards you should edit file *vendor/crowdtruth/mturk/src/config/config.php* as required. In particular, you need to provide your accesskey and secretkey.

For more information visit: http://crowdtruth.org/
