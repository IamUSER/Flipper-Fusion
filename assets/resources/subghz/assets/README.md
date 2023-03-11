#Sub-Ghz Frequencies in Xtreme

Officially supported frequencies: 300-350 MHz, 387-467.75 MHz, and 779-928 MHz (from [CC1101 chip docs](https://www.ti.com/product/CC1101))<br>
Unofficially supported frequencies: 281-361 MHz, 378-481 MHz, and 749-962 MHz (from [YARD Stick One/CC1111 Docs](https://greatscottgadgets.com/yardstickone/))

Currently no other Flipper firmware allows anything outside of the officially supported CC1101 specs without editing files that get overwritten with every update.
Xtreme has these options easily togglable in the Xtreme Settings app.

**NOTE: Going outside the supported frequencies may DAMAGE YOUR FLIPPER AMP.<br>
Please understand what you're doing if trying to break out of official frequencies.**

You'll need to edit the [extended range file](https://github.com/IamUSER/Flipper-Fusion/blob/main/documentation/DangerousSettings.md) to enable frequencies outside of the Official above.

# CAUTION within 402-408 range!<br>Medical devices can operate here.

This range is purposefully not included in my file above.
