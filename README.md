# SilverStripe supported module skeleton

This module provides a set of icons primarily used by the elements in the
[`syntro/silverstripe-elemental-bootstrap-collection`](https://github.com/syntro-opensource/silverstripe-elemental-bootstrap-collection)
and other elements maintained by us.

You can use these icons standalone.


## Requirements

* none

## Installation
Add some installation instructions here, having a 1 line composer copy and paste is useful.
Here is a composer command to create a new module project. Ensure you read the
['publishing a module'](https://docs.silverstripe.org/en/developer_guides/extending/how_tos/publish_a_module/) guide
and update your module's composer.json to designate your code as a SilverStripe module.

```
composer require syntro/silverstripe-elemental-icons
```

### Available icons


| Icon | Name |
| ---- | ---- |
| <img src="https://www.github.com/syntro-opensource/silverstripe-elemental-icons/raw/master/client/src/styles/alert.svg?sanitize=true" alt="alert" width="32" height="32"> | `alert` |
| <img src="https://www.github.com/syntro-opensource/silverstripe-elemental-icons/raw/master/client/src/styles/features.svg?sanitize=true" alt="features" width="32" height="32"> | `features` |
| <img src="https://www.github.com/syntro-opensource/silverstripe-elemental-icons/raw/master/client/src/styles/illustrated-features.svg?sanitize=true" alt="illustrated-features" width="32" height="32"> | `illustrated-features` |
| <img src="https://www.github.com/syntro-opensource/silverstripe-elemental-icons/raw/master/client/src/styles/gallery.svg?sanitize=true" alt="gallery" width="32" height="32"> | `gallery` |
| <img src="https://www.github.com/syntro-opensource/silverstripe-elemental-icons/raw/master/client/src/styles/spotlight.svg?sanitize=true" alt="spotlight" width="32" height="32"> | `spotlight` |
| <img src="https://www.github.com/syntro-opensource/silverstripe-elemental-icons/raw/master/client/src/styles/staff.svg?sanitize=true" alt="staff" width="32" height="32"> | `staff` |
| <img src="https://www.github.com/syntro-opensource/silverstripe-elemental-icons/raw/master/client/src/styles/testimonial.svg?sanitize=true" alt="testimonial" width="32" height="32"> | `testimonial` |

## License
See [License](license.md)


## Documentation

To use, simply set the icon in the class using the `elemental-icon-` prefix:

```php
    /**
     * @var string
     */
    private static $icon = 'elemental-icon-alert';
```


## Maintainers
 * Matthias Leutenegger <hello@syntro.ch>

## Bugtracker
Bugs are tracked in the issues section of this repository. Before submitting an issue please read over
existing issues to ensure yours is unique.

If the issue does look like a new bug:

 - Create a new issue
 - Describe the steps required to reproduce your issue, and the expected outcome. Unit tests, screenshots
 and screencasts can help here.
 - Describe your environment as detailed as possible: SilverStripe version, Browser, PHP version,
 Operating System, any installed SilverStripe modules.

Please report security issues to the module maintainers directly. Please don't file security issues in the bugtracker.

## Development and contribution
If you would like to make contributions to the module please ensure you raise a pull request and discuss with the module maintainers.
