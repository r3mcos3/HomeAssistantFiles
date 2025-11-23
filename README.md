# Home Assistant Configuration Files

This repository contains various configuration files for my Home Assistant setup, including automations, scrape sensors, blueprints, and custom dashboard cards.

## Contents:

-   `lights_on.yaml`: Automation to manage lighting, typically used for specific scenarios or routines.
-   `phone_alarm_automation.yaml`: Automation that triggers actions based on phone alarm states, such as adjusting lighting or playing media.
-   `scrape.yaml`: Configuration for web scraping sensors, primarily used for tracking fuel prices and other dynamic data.
-   `blueprints/`:
    -   `Sentinel Sight PRO.yaml`: A Home Assistant Blueprint, likely for advanced motion detection or security camera integration.
    -   `Sentinel Sight.yaml`: A Home Assistant Blueprint, possibly a standard version of the motion detection/security camera integration.
    -   `volume_control3.yaml`: A Home Assistant Blueprint for controlling media player volumes.
-   `person card/`:
    -   `person_card.yaml`: Configuration for a custom Lovelace person card, used to display information about individuals in the Home Assistant dashboard.
    -   `README.md`: Documentation specific to the person card.

## Usage:

These files are designed to be integrated into a Home Assistant installation. You can copy the relevant `.yaml` files into your Home Assistant configuration directory, ensuring proper indentation and adherence to Home Assistant's configuration structure. Blueprints should be imported via the Home Assistant UI.

## Contributing:

Feel free to explore and adapt these configurations for your own Home Assistant setup. If you have suggestions or improvements, please open an issue or pull request.