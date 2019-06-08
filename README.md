
# User Initials Photo plugin for Craft CMS 3.x

A plugin to assign profile picture of user with their name initials.

<img src="https://ui-avatars.com/assets/promo-new.png">

*Image via [[https://ui-avatars.com](https://ui-avatars.com)]*

## Requirements

This plugin requires Craft CMS 3.0.0 or later.

## Installation

To install the plugin, follow these instructions.

1. Open your terminal and go to your Craft project:

        cd /path/to/project

2. Then tell Composer to load the plugin:

        composer require hashtagerror/user-initials-photo

3. In the Control Panel, go to Settings → Plugins and click the “Install” button for **User Initials Photo**.

## User Initials Photo Overview

This plugins automatically assign a user photo with their initials, when they are registered. The image is generated from [UI Avatars](https://ui-avatars.com). The initials generated in the photo are in following priority:
* Firstname Lastname
* Firstname
* Lastname
* Username
* Email

Whichever found first will be used as the initials.

## Using User Initials Photo

To use the plugin make sure a volume is assigned in `User Photo Location` in your User Settings. 
By default the plugin assings Photos to new user only. To assign photos to old users too, uncheck `Assign Images to New User Only` in Plugin Setting page.
To assign photos to all Users at once, Go to plugin section page and click `Assign`.

NOTE: If you are updating plugin from `v1.0.0` to `v1.1.0` or above you must have to do a `composer remove hashtagerrors/hashtagerror/user-initials-photo` and then `composer require hashtagerror/user-initials-photo` to get plugin setting and section page.

## User Initials Photo Roadmap

While there is not a lot to do in this plugin, but new ideas are always welcome. You can post your idea or request [here](https://github.com/hashtagerrors/userinitialsphoto/issues/new) 

### Loved It? 

Show your Love and Support by buying me a cup of Coffee !

<a href="https://ko-fi.com/hashtagerrors" target="_blank"><img src="http://www.hashtagerrors.com/assets/uploads/buy-me-a-coffee.png" alt="Buy Me A Coffee" width="200"></a>

Brought to you by [Hashtag Errors](http://www.hashtagerrors.com)
