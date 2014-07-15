# Control

nib styling for a form control. See [nib-health-funds](https://github.com/nib-health-funds/control) for JS.

## Markup

For example:

    <div class="control">
        <label class="control-label" for="first-name-input">First name</label>

        <div class="control-input-wrapper">
            <input type="text" class="control-input control-input--text" id="first-name-input" autofocus/>
            <div class="control-feedback-icon no-select">
                <div class="control-feedback-pointer"></div>
            </div>
        </div>

        <div class="control-feedback-message no-select">
            <p class="control-feedback-message__text"></p>
        </div>
    </div>