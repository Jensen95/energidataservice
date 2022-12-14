This is a custom component for Home Assistant to integrate Day Ahead spotprices for electricity, from Energidataservice

For Tips & Tricks, see the [wiki pages](https://github.com/MTrab/energidataservice/wiki)

PLEASE NOTE!! This integration CANNOT be used with fixed price contracts! Perhaps in a future release, but NOT as it is right now.

### Installation:

#### HACS

- Ensure that HACS is installed.
- Search for and install the "Energi Data Service" integration.
- Restart Home Assistant.

#### Manual installation

- Download the latest release.
- Unpack the release and copy the custom_components/energidataservice directory into the custom_components directory of your Home Assistant installation.
- Restart Home Assistant.

## Setup

Shortcut:<br>
[![](https://my.home-assistant.io/badges/config_flow_start.svg)](https://my.home-assistant.io/redirect/config_flow_start/?domain=energidataservice)

* Go to Home Assistant > Settings > Integrations
* Add "Energi Data Service" integration *(If it doesn't show, try CTRL+F5 to force a refresh of the page)*
* Select area

Voila

## Translation

To handle submissions of translated strings I'm using [Lokalise](https://lokalise.com/).<br/>
They provide an amazing platform that is easy to use and maintain.<br/>
<br/>
To help out with the translation of this custom_component you need an account on Lokalise.<br/>
The easiest way to get one is to [click here](https://lokalise.com/login/) then select "Log in with GitHub".<br/>
<br/>
When you have created your account, [clich here](https://app.lokalise.com/public/6177700562fcdf14ea2483.26249049/) to join the project on Lokalise.<br/>
<br/>
Check Lokalise documentation [here](https://docs.lokalise.com/en/) - it's really good.<br/>
<br/>
All languages for the countries currently supported by the integration, should be added to Lokalise - if you are missing a language, then please [submit a feature request](https://github.com/MTrab/energidataservice/issues/new?assignees=&labels=feature+request&template=feature_request.md&title=%5BFR%5D%3A+%3Ctitle%3E)<br/>
<br/>
Contributions to the translations will be updated on every release of this component.
