# iq_metatag_extension
Meta package to include metatag and schema_metatag in 
a project with optimized settings.

## Setup & Installation
Install module
    composer require iqual/iq_metatag_extension
    drush en iq_metatag_extension

This will automatically set metatag's pivot element to "::" if it's ",".
Includes "Escape html instead of stripping html tags" (https://dgo.to/3400436).
