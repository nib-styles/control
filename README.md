# Control

Control styling.

## Markup

For example:

		<div class="control t-first-name-control rg-mb3at4 js-first-name-control">
			<label class="control-label" for="first-name-input">First name</label>

			<div class="rg-4of6 parent">
				<input type="text" class="control-input control-input--text t-first-name js-first-name-control-input" id="first-name-input" maxlength="24" data-ga-category="Name" data-ga-label="First Name" autofocus value="@Model.PersonalDetails.PolicyHolder.FirstName" />
				<div class="control-feedback-icon no-select">
					<div class="control-feedback-pointer"></div>
				</div>
			</div>

			<div class="control-feedback-message no-select js-feedback-message">
				<p class="control-feedback-message__text js-feedback-message-text t-feedback-message"></p>
			</div>
		</div>