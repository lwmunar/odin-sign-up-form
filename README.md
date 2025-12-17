# odin-sign-up-form
TOP's Project: Sign-up Form

Create a stylish sign-up form with basic functionalities and user error correction.

Notes:
- using :root for reset does not remove properly:

:root {
    margin: 0;
}

instead, use *:

* {
    margin: 0;
}

- link buttons that are outside a form using specified form's ID attribute: <button ... form="formID">
- when using clamp, use a scaling parameter for the middle value e.g. clamp(100px,70%,300px), otherwise, the element feels static and block-y