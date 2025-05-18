# Gamepad API (gamepad simple game)

## Some important notes

- addEventListeners

    - resize has effect of when window size is changed and canvas stays full sized

    - gamepadconnect has effect of when user connects gamepad to PC

    - gamepaddisconnect has effect of when user disconnects gamepad from PC

- stickDeadZone

    - value as 0.4 has effect of diagonally movement (8-way movement)

    - value as 0.8 has effect of up/down and left/right movement only (4-way movement)