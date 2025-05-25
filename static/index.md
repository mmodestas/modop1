# About
ESP8266-based P1 electricity meter reader.

This version is adapted from various other implementations using the DSMR library, modified specifically to align with the addresses and descriptions defined in the Lithuanian P1 specification (provided by ESO).

# Features

I made this to use external antenna, as with standard D1 Mini on board antena signal ir poor in metal outdoor cabinet. Signal quality is considerably better when putting antenna outside.

# Installation

You can use the button below to install the pre-built firmware directly to your device via USB from the browser.

<esp-web-install-button manifest="firmware/modop1reader.manifest.json"></esp-web-install-button>

<script type="module" src="https://unpkg.com/esp-web-tools@10/dist/web/install-button.js?module"></script>
