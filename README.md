Extending Yii with Geospatial Functions
=======================================
Extending Yii with Geospatial Functions like Forward and Reverse Geocoding, PointPicker, using Openlayers mapping libraries   etc

Installation
------------

The preferred way to install this extension is through [composer](http://getcomposer.org/download/).

Either run

```
php composer.phar require --prefer-dist ramshresh/yii2-geo "*"
```

or add

```
"ramshresh/yii2-geo": "*"
```

to the require section of your `composer.json` file.


Usage
-----

Once the extension is installed, simply use it in your code by  :

```php
<?= \ramshresh\yii2\geo\AutoloadExample::widget(); ?>```