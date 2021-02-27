# Interoperability

The App is designed to differentiate the particular use case (G6 or G6 Pro) based on the entered Transmitter ID during Transmitter pairing. The App will then select the appropriate workflow, either G6 or G6 Pro, based upon the Transmitter ID entered by the user. When a user switches from G6 or G6 Pro, their previously selected settings will be reset to the default settings. They will then be asked to re-enter or reset their Low and High Alert alert threshold.

REQ110520
:   The app shall allow the user to enter two unique ID types:

    - A TX ID beginning with the numeral "3"
    - A TX ID beginning with the numeral "8"

REQ110529
:   A user can enter a different TX ID type at the following places in the app:

    - via Enter TX ID screen in the Set-up wizard, during on-boarding
    - via the Transmitter submenu in Settings
    - via Transmitter Not Found on Trend-screen

REQ110530
:   WHILE G6 Pro is OFF,
    A user can enter a different TX ID type at the following place in the app:
    - via the Stop Sensor in Settings

REQ110531
:   When a user enters a different TX ID type than the last session via the Transmitter sub menu, the Stop Sensor function in Settings, via Transmitter not Found on trend-screen, the app shall display a series of safety screens to the user, and request that they understand each, prior to proceeding to the next.

REQ110522
:   When a user enters a different ID Type identifier, since their last sensor session, the app shall reset settings to the factory defaults.

REQ110524
:   WHILE G6 Pro is ON,
    After re-setting the user's settings to factory defaults, the app shall display a screen informing the user that settings have been reset to G6 Pro factory default.

REQ110525
:   WHILE G6 Pro is OFF,
    After re-setting the user's settings to factory defaults, the app shall display a screen informing the user that settings have been reset to G6 factory default.

REQ110903
:   After re-setting the user's settings to factory defaults, the app shall display a screen informing the user to go to app settings to check all setting values.

REQ110527
:   After re-setting the user's settings to factory defaults, the app shall request the user re-set their Low alert default threshold.

REQ110528
:   After re-setting the user's settings to factory defaults, the app shall request the user re-set their High alert default threshold.
