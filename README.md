# 💡 Light Switch for Bootstrap 5

<p align="center">
<b>Basic Bootstrap 5 custom checkbox to use night mode in your web site.</b>
</p>

## Under the hood

Switching to dark mode is done by toggling HTML tags that includes `-dark` or `-light` as a class. Performed by DOM manipulation using JavaScript based on the default system theme. **Local storage** is used to save the choice under the name: _lightSwitch_

## Installing

- Download the latest release [v0.1.4](https://github.com/lucthienphong1120/dark-mode-switch/)

- Clone via `git clone https://github.com/lucthienphong1120/dark-mode-switch.git`
- Install with [npm](https://www.npmjs.com/package/light-switch-bootstrap) `npm i light-switch-bootstrap`

## Usage

Add custom checkbox to your html file then reference the `switch.js` script:

```html
<div class="form-check form-switch ms-auto mt-3 me-3" id="formSwitch">
    <label class="form-check-label ms-3" for="inputSwicher">
        <i class="fas fa-sun light-mode"></i>
        <i class="fas fa-moon dark-mode d-none"></i>
        </label>
    <input class="form-check-input" type="checkbox" id="inputSwicher" />
</div>

<script src="dark-mode-switch.js" />
```

### About Usage

Designed for the plain Bootstrap 5 theme. If you're using custom themes then, you will probably have to customize it for better results.

## Example Implementation

[Bootstrap 5 Demo](https://lucthienphong1120.github.io/dark-mode-switch/)
