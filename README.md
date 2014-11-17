# Control

nib styling for a form control. See [nib-health-funds](https://github.com/nib-health-funds/control) for JS.

## Markup

For example:

    <div class="control">
        <label class="control__label" for="first-name-input">First name</label>

        <div class="control__input">
            <input type="text" class="control-input-text" id="first-name-input" autofocus/>
            <i class="control-feedback-icon no-select"></i>
        </div>

        <div class="control-feedback-message no-select">
            <p class="control-feedback-message__text"></p>
        </div>
    </div>