# Plant for the Planet Plugin

Weplant plugin is developed by [Plant-for-the-Planet Foundation](https://www.plant-for-the-planet.org) for extending the functionality of the [Trillion Tree Campaign App](https://www.trilliontreecampaign.org) to wordpress.

### Features

#### 1. Treecounter Shortcode

    [weplant profile="slug"]
    
    [weplant]
    
__Steps to Enable Treecounter shortcode -__

1. Activate Weplant Plugin
2. Go to Tree Settings
3. Under Settings, Check/Tick Treecounter option
4. Add your Trillion Tree Campaign Profile Link in the Input Field
5. Click on Save Changes
6. Your Treecounter Shortcode will apear in a box below
7. Use it on any Wordpress Page/Post

If you want display multiple treecounters on your website. Simply replace `profile="slug"` by your profile slug.
For eg. in `https://www.trilliontreecampaign.org/t/felix-finkbeiner-1` the slug is `felix-finkbeiner-1`. So your shortcode for this profile will be `[weplant profile="felix-finkbeiner-1"]`

If no profile argument it passed, the global trillion treecounter is displayed.  

#### 2. Projects Shortcode Shortcode _(Coming Soon)_

    [weplant project="id" type="preview"]
    
    [weplant project="id" type="detail"]

#### 3. Competitions Shortcode Shortcode _(Coming Soon)_

    [weplant competition="id" type="leaderboard" count="20"]
    
    [weplant competition="id" type="preview"]

#### 4. Donation Integration _(Should be TPO on TTC Platform)_

Tree Planting Organisations can take donations on their own websites and register trees on their Trillion Tree Campaign Profile.

__Features:__

* Take Donations on your own website
* Register Trees on the Trillion Tree Campaign 
* Manage Donors on your own platform
* Display Treecounter progress
* Calculate and Display Tree Count equivalent to the Donation amount on Donation Form

__Requirements:__

* Only GiveWP Donation Plugin is Supported
* Verified TPO Account on TTC Platform
* API Access Key of your TTC Account
* Treecount Registered on TTC Profile

__How to Enable:__

To enable this development feature `WEPLANT_DONATIONS` should be defined as `true` in wp-config.php

__Declaration:__

_This feature is in development stage_

#### 5. Woocommerce Support _(Future Releases)_

WooCommerce Stores will be able to allow buyers to plant trees during checkout process. Stores can either choose to send the emails with a code to buyers, or ask the Plant-for-the-Planet app to contact the buyer directly.


### Support

Support for this plugin is provided by:

support@plant-for-the-planet.org

Plant-for-the-Planet Foundation<br/>
Am Bahnhof 1,<br/>
Uffing Am Staffelsee<br/>
82449, Bavaria<br/>
Germany
