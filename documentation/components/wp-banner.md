# Banner webpart

This webpart provides you the ability to add a variable height image banner with a linkable title.

![Bannner](../../assets/images/components/part-banner.gif)

## How to use this webpart on your web pages

1. Place the page you want to add this webpart to in edit mode.
2. Search for and insert the **Banner** webpart.
3. Configure the webpart to update its properties.

## Configurable Properties

The `Banner` webpart can be configured with the following properties:

| Label | Property | Type | Required | Description |
| ---- | ---- | ---- | ---- | ---- |
| Overlay image text | bannerText | string | no | The text message or title you want displayed on the banner image |
| Image URL | bannerImage | string | no | The url of the banner image |
| Link URL | bannerLink | string | no | The hyperlink url of the bannerText link |
| Banner height | bannerHeight | number | no | Provides the fixed height of the banner image |
| Enable parallax effect | useParallax | toggle | no | Enable if you want to include parallax effect on vertical scrolling |


# Installing the web part

See getting started from [SP-Starter-Kit repository readme](https://github.com/SharePoint/sp-starter-kit). 

You can also download just the [SharePoint Framework solution package (spppkg) file](https://github.com/SharePoint/sp-starter-kit/blob/master/package/sharepoint-starter-kit.sppkg) and install that to your tenant. This web part does not have external dependencies.

# Screenshots

![Bannner](../../assets/images/components/part-banner.png)

# Source Code

https://github.com/SharePoint/sp-starter-kit/tree/master/solution/src/webparts/banner

# Minimal Path to Awesome

- Clone this repository
- Move to Solution folder
- in the command line run:
  - `npm install`
  - `gulp serve`

# Version history

Version|Date|Comments
-------|----|--------
1.0|May 2018|Initial release


![](https://telemetry.sharepointpnp.com/sp-starter-kit/documentation/components/wp-banner)