# hass_blueprints
Home Assistant blueprints


<br>
<b>Window_open_and_Heating_Protection.yaml</b>

    Turns off thermostat(s) when a window is opened or tilted and restores their
    previous settings once the window is fully closed again. Optionally sends a
    notification if the window stays open while it is cold outside.

<br>
<b>Window_open_and_Heating_Protection_v12.yaml</b>

    Turns off thermostat(s) when a window is opened or tilted and restores their
    previous settings once the window is fully closed again. Optional delays
    avoid reacting to short airing. If the window stays open while it is cold
    outside, a notification is sent, followed by repeat reminders with action
    buttons (turn heating back on / snooze). Notifications are dismissed when
    the window closes.
