<!-- MATERIAL -->
<link href="https://unpkg.com/material-components-web@latest/dist/material-components-web.min.css" rel="stylesheet">
<link rel="stylesheet" href="https://fonts.googleapis.com/icon?family=Material+Icons">
<script src="https://unpkg.com/material-components-web@latest/dist/material-components-web.min.js"></script>
<!-- END MATERIAL -->

<style>
.link-no-underline:link {
	text-decoration: none;
}
.link-no-underline:visited {
	text-decoration: none;
}
.link-no-underline:hover {
	text-decoration: none;
}
.link-no-underline:active {
	text-decoration: none;
}

.repo-language-color {
	position: relative;
	top: 1px;
	display: inline-block;
	width: 12px;
	height: 12px;
	border-radius: 50%;
}

.flex-container {
	display: flex;
	flex-direction: row;
}

.project-card {
	width: 50%;
	height: 150px;
	margin: 5px;
}

@media screen and (max-width: 600px) {
	.flex-container {
		flex-direction: column;
	}
	.project-card {
		width: 100%;
	}
}
</style>

<div id="root-div" class="mdc-typography">
	<header class="mdc-top-app-bar mdc-top-app-bar--short">
		<div class="mdc-top-app-bar__row">
			<section class="mdc-top-app-bar__section mdc-top-app-bar__section--align-start">
				<span class="mdc-top-app-bar__title">DKittenz's GitHub Profile</span>
			</section>
		</div>
	</header>
	<div style="height: 50px;">
		<!-- Empty space after the top bar -->
	</div>
	<h1 class="mdc-typography--headline5">👋 Hi, I'm DKittenz</h1>
	<ul>
		<li>
			<span class="mdc-typography--body1">🔭 I’m currently working on a Roblox game with my friend.</span>
		</li>
		<li>
			<span class="mdc-typography--body1">😄 Pronouns: He/him</span>
		</li>
		<li>
			<span class="mdc-typography--body1">⚡ Fun fact: I love cats!</span>
		</li>
		<li>
			<span class="mdc-typography--body1">⚡ Another fun fact: I indent using tabs <span class="mdc-typography--overline">#TeamTabs</span>.</span>
		</li>
		<li>
			<span class="mdc-typography--body1">⚡ Third fun fact: I like Material Design, as you can see from this README.</span>
		</li>
	</ul>
	<h1 class="mdc-typography--headline5">Connect with me</h1>
	<a class="mdc-button mdc-button--raised link-no-underline" href="https://kittenz.dev">
		<div class="mdc-button__ripple"></div>
		<i class="material-icons mdc-button__icon" aria-hidden="true">language</i>
		<span class="mdc-button__label">Website</span>
	</a>
	<a class="mdc-button mdc-button--raised link-no-underline" href="mailto:kitten@kittenz.dev">
		<div class="mdc-button__ripple"></div>
		<i class="material-icons mdc-button__icon" aria-hidden="true">email</i>
		<span class="mdc-button__label">Email</span>
	</a>
	<a class="mdc-button mdc-button--raised link-no-underline" href="https://twitter.com/Dev_Kittenz">
		<div class="mdc-button__ripple"></div>
		<i class="mdc-button__icon" aria-hidden="true"><img src="https://raw.githubusercontent.com/DKittenz/DKittenz/master/icons/Twitter_Logo.svg" width="24px" height="24px"></img></i>
		<span class="mdc-button__label">Twitter</span>
	</a>
	<div style="height: 10px;">
		<!-- Empty space after the buttons -->
	</div>
	<h1 class="mdc-typography--headline5">Projects</h1>
	<div class="flex-container">
		<div class="mdc-card project-card" style="float: left;">
			<div class="mdc-card__primary-action">
				<div class="mdc-card__media mdc-card__media--square">
					<div class="mdc-card__media-content">
						<h1 class="mdc-typography--headline6 mdc-theme--primary" style="margin-left: 15px; margin-top: 10px;">kittenz.dev</h1>
						<h1 class="mdc-typography--body1 mdc-theme--on-surface" style="margin-left: 15px; margin-top: 10px;">My website, nothing special.</h1>
					</div>
				</div>
			</div>
			<div class="mdc-card__actions">
				<div class="mdc-card__action-buttons">
					<a class="mdc-button mdc-card__action mdc-card__action--button link-no-underline" href="https://github.com/DKittenz/kittenz.dev">
						<div class="mdc-button__ripple"></div>
						<span class="mdc-button__label">Repository</span>
					</a>
				</div>
				<div class="mdc-card__action-icons">
					<span class="mdc-card__action mdc-card__action--icon">
						<svg mr="2" height="16" viewBox="0 0 16 16" version="1.1" width="16" aria-hidden="true"><path fill-rule="evenodd" d="M8.75.75a.75.75 0 00-1.5 0V2h-.984c-.305 0-.604.08-.869.23l-1.288.737A.25.25 0 013.984 3H1.75a.75.75 0 000 1.5h.428L.066 9.192a.75.75 0 00.154.838l.53-.53-.53.53v.001l.002.002.002.002.006.006.016.015.045.04a3.514 3.514 0 00.686.45A4.492 4.492 0 003 11c.88 0 1.556-.22 2.023-.454a3.515 3.515 0 00.686-.45l.045-.04.016-.015.006-.006.002-.002.001-.002L5.25 9.5l.53.53a.75.75 0 00.154-.838L3.822 4.5h.162c.305 0 .604-.08.869-.23l1.289-.737a.25.25 0 01.124-.033h.984V13h-2.5a.75.75 0 000 1.5h6.5a.75.75 0 000-1.5h-2.5V3.5h.984a.25.25 0 01.124.033l1.29.736c.264.152.563.231.868.231h.162l-2.112 4.692a.75.75 0 00.154.838l.53-.53-.53.53v.001l.002.002.002.002.006.006.016.015.045.04a3.517 3.517 0 00.686.45A4.492 4.492 0 0013 11c.88 0 1.556-.22 2.023-.454a3.512 3.512 0 00.686-.45l.045-.04.01-.01.006-.005.006-.006.002-.002.001-.002-.529-.531.53.53a.75.75 0 00.154-.838L13.823 4.5h.427a.75.75 0 000-1.5h-2.234a.25.25 0 01-.124-.033l-1.29-.736A1.75 1.75 0 009.735 2H8.75V.75zM1.695 9.227c.285.135.718.273 1.305.273s1.02-.138 1.305-.273L3 6.327l-1.305 2.9zm10 0c.285.135.718.273 1.305.273s1.02-.138 1.305-.273L13 6.327l-1.305 2.9z"></path></svg>
						<span style="margin-left: 4px;">UNLICENSED</span>
					</span>
					<span class="mdc-card__action mdc-card__action--icon">
						<span class="repo-language-color" style="background-color: #2b7489"></span>
						<span style="margin-left: 2px;">TypeScript</span>
					</span>
				</div>
			</div>
		</div>
		<div class="mdc-card project-card">
			<div class="mdc-card__primary-action">
				<div class="mdc-card__media mdc-card__media--square">
					<div class="mdc-card__media-content">
						<h1 class="mdc-typography--headline6 mdc-theme--primary" style="margin-left: 15px; margin-top: 10px;">Obby Time</h1>
						<h1 class="mdc-typography--body1 mdc-theme--on-surface" style="margin-left: 15px; margin-top: 10px;">Obby Time is a competitive obstacle run game on Roblox.</h1>
					</div>
				</div>
			</div>
			<div class="mdc-card__actions">
				<div class="mdc-card__action-buttons">
					<a class="mdc-button mdc-card__action mdc-card__action--button link-no-underline" href="https://www.roblox.com/games/4287394397/Obby-Time">
						<div class="mdc-button__ripple"></div>
						<span class="mdc-button__label">Play</span>
					</a>
				</div>
				<div class="mdc-card__action-icons">
					<span class="mdc-card__action mdc-card__action--icon">
						<svg mr="2" height="16" viewBox="0 0 16 16" version="1.1" width="16" aria-hidden="true"><path fill-rule="evenodd" d="M8.75.75a.75.75 0 00-1.5 0V2h-.984c-.305 0-.604.08-.869.23l-1.288.737A.25.25 0 013.984 3H1.75a.75.75 0 000 1.5h.428L.066 9.192a.75.75 0 00.154.838l.53-.53-.53.53v.001l.002.002.002.002.006.006.016.015.045.04a3.514 3.514 0 00.686.45A4.492 4.492 0 003 11c.88 0 1.556-.22 2.023-.454a3.515 3.515 0 00.686-.45l.045-.04.016-.015.006-.006.002-.002.001-.002L5.25 9.5l.53.53a.75.75 0 00.154-.838L3.822 4.5h.162c.305 0 .604-.08.869-.23l1.289-.737a.25.25 0 01.124-.033h.984V13h-2.5a.75.75 0 000 1.5h6.5a.75.75 0 000-1.5h-2.5V3.5h.984a.25.25 0 01.124.033l1.29.736c.264.152.563.231.868.231h.162l-2.112 4.692a.75.75 0 00.154.838l.53-.53-.53.53v.001l.002.002.002.002.006.006.016.015.045.04a3.517 3.517 0 00.686.45A4.492 4.492 0 0013 11c.88 0 1.556-.22 2.023-.454a3.512 3.512 0 00.686-.45l.045-.04.01-.01.006-.005.006-.006.002-.002.001-.002-.529-.531.53.53a.75.75 0 00.154-.838L13.823 4.5h.427a.75.75 0 000-1.5h-2.234a.25.25 0 01-.124-.033l-1.29-.736A1.75 1.75 0 009.735 2H8.75V.75zM1.695 9.227c.285.135.718.273 1.305.273s1.02-.138 1.305-.273L3 6.327l-1.305 2.9zm10 0c.285.135.718.273 1.305.273s1.02-.138 1.305-.273L13 6.327l-1.305 2.9z"></path></svg>
						<span style="margin-left: 4px;">PROPRIETARY</span>
					</span>
					<span class="mdc-card__action mdc-card__action--icon">
						<span class="repo-language-color" style="background-color: #000080"></span>
						<span style="margin-left: 2px;">Lua</span>
					</span>
				</div>
			</div>
		</div>
	</div>
</div>
