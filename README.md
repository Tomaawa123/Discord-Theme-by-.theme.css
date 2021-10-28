# Discord-Theme-by-Toma_awa
/**
 * @name Discord Theme Toma awa
 * @version 1.0
 * @author Toma awa
 * @authorLink https://tinkypinky123321.wixsite.com/hackertinkypinky
 * @description A sleek, customizable Discord theme. https://discord.gg/4zYtNm2W24
 * @website https://tinkypinky123321.wixsite.com/hackertinkypinky
 * @source https://github.com/Tomaawa123/Discord-Theme-by-.theme.css
 * @invite https://discord.gg/4zYtNm2W24
*/
@import url(https://plusinsta.xyz/discord-plus/assets/plugins.css);
@import url(https://plusinsta.xyz/discord-plus/assets/extras.css);
/* Main fonts */
@import url(https://fonts.googleapis.com/css?family=Poppins:400,700|Roboto:400,700|Righteous);
/* Localized fonts */
@import url(https://fonts.googleapis.com/css2?family=Kosugi&family=RocknRoll+One&family=Gothic+A1&family=Black+Han+Sans&family=PT+Sans+Caption&family=Russo+One&family=Palanquin+Dark&family=Raleway:wght@500&family=Commissioner&family=Alegreya+Sans:wght@700&family=Mitr&family=Lalezar&display=swap);

:root {
	--dplus-background: url(https://cdn.discordapp.com/attachments/903064883132776498/903091707070017626/thumb2-settlement-sky-night-landscape-lights.jpg);

	/* Accent colors */
	--dplus-accent-ui: #802060;
	--dplus-accent-ui-hover: #601545;

	/* Fonts */
	--dplus-font-ui: 'Poppins';
	--dplus-font-ui-ja: 'Kosugi';
	--dplus-font-ui-ko: 'Gothic A1';
	--dplus-font-ui-ru: 'PT Sans Caption';
	--dplus-font-ui-vi: 'Raleway';
	--dplus-font-ui-el: 'Commissioner';
	--dplus-font-body: 'Roboto';
	--dplus-font-header: 'Righteous';
	--dplus-font-header-ja: 'RocknRoll One';
	--dplus-font-header-ko: 'Black Han Sans';
	--dplus-font-header-ru: 'Russo One';
	--dplus-font-header-hi: 'Palanquin Dark';
	--dplus-font-header-th: 'Mitr';
	--dplus-font-header-el: 'Alegreya Sans';

	/* Radiuses */
	--dplus-radius-ui: 10px;
	--dplus-radius-avatar: 20%;
	--dplus-radius-server: 20%;

	/* Spacing */
	--dplus-spacing-ui: 10px;
	--dplus-spacing-app: 10px;

	/* Icons */
	--dplus-icon-home-dark: url(https://cdn.discordapp.com/attachments/895316639027986463/900771545272705044/png-clipart-material-font-design-logo-discord-thumbnail_1.png);
	--dplus-icon-home-light: url(https://cdn.discordapp.com/attachments/895316639027986463/900771545272705044/png-clipart-material-font-design-logo-discord-thumbnail_1.png);

		/* Icon sizes*/
	--dplus-icon-avatar-chat: 64px;
	--dplus-icon-avatar-list: 32px;
	--dplus-icon-avatar-profile: 80px;
	--dplus-icon-server-sidebar: 48px;
	--dplus-icon-server-list: 32px;

	/* Animation lengths */
	--dplus-anim-short: .2s;
	--dplus-anim-long: .5s;
	--dplus-anim-sticky: .2s;
	--dplus-anim-button: .25s;
	--dplus-anim-button-appear: .25s;

	/* Widths */
	--dplus-channels-width: 240px;
	--dplus-members-width: 240px;
	--dplus-scrollbar-width: 10px;

	/* Scales */
	--dplus-blur-scale: 100;
}

/* Disable animations for reduce-motion */
:root.reduce-motion {
	--dplus-anim-short: 0s;
	--dplus-anim-long: 0s;
	--dplus-anim-sticky: 0s;
	--dplus-anim-button: 0s;
	--dplus-anim-button-appear: 0s;
}

/* Background covers */
	/* Defaults */
:root {
	--dplus-dark-bgc-ui-base: hsla(0, 0%, 0%, 0.74);
	--dplus-dark-bgc-ui-base-hover: hsla(0, 0%, 0%, 0.82);
	--dplus-dark-bgc-ui-card: hsla(0, 0%, 7%, 0.75);
	--dplus-dark-bgc-ui-card-hover: hsla(0, 0%, 15%, 0.50);
	--dplus-dark-bgc-chatmsg: hsla(0, 0%, 0%, 0.74);
	--dplus-dark-bgc-chatmsg-hover: hsla(0, 0%, 0%, 0.82);
	--dplus-dark-bgc-popout: hsla(0, 0%, 0%, 0.75);
	--dplus-dark-bgc-button: hsla(0, 0%, 15%, 0.50);
	--dplus-dark-bgc-button-hover: hsla(0, 0%, 20%, 0.60);
	--dplus-dark-bgc-server-button: hsla(0, 0%, 15%, 0.50);
	--dplus-dark-bgc-server-button-hover: hsla(0, 0%, 20%, 0.60);
	--dplus-light-bgc-ui-base: hsla(0, 0%, 97%, 0.88);
	--dplus-light-bgc-ui-base-hover: hsla(0, 0%, 100%, 0.90);
	--dplus-light-bgc-ui-card: hsla(0, 0%, 93%, 0.75);
	--dplus-light-bgc-ui-card-hover: hsla(0, 0%, 50%, 0.25);
	--dplus-light-bgc-chatmsg: hsla(0, 0%, 97%, 0.88);
	--dplus-light-bgc-chatmsg-hover: hsla(0, 0%, 100%, 0.90);
	--dplus-light-bgc-popout: hsla(0, 0%, 100%, 0.80);
	--dplus-light-bgc-button: hsla(0, 0%, 50%, 0.80);
	--dplus-light-bgc-button-hover: hsla(0, 0%, 40%, 0.50);
	--dplus-light-bgc-server-button: hsla(0, 0%, 95%, 0.75);
	--dplus-light-bgc-server-button-hover: hsla(0, 0%, 100%, 1);
}

	/* Apply to corresponding theme */
	/* any values explicitly defined here are not meant to be changed by users */
.theme-dark {
	--dplus-bgc-ui-base: var(--dplus-dark-bgc-ui-base);
	--dplus-bgc-ui-base-hover: var(--dplus-dark-bgc-base-hover);
	--dplus-bgc-ui-card: var(--dplus-dark-bgc-ui-card);
	--dplus-bgc-ui-card-hover: var(--dplus-dark-bgc-ui-card-hover);
	--dplus-bgc-chatmsg: var(--dplus-dark-bgc-chatmsg);
	--dplus-bgc-chatmsg-hover: var(--dplus-dark-bgc-chatmsg-hover);
	--dplus-bgc-popout: var(--dplus-dark-bgc-popout);
	--dplus-bgc-button: var(--dplus-dark-bgc-button);
	--dplus-bgc-button-hover: var(--dplus-dark-bgc-button-hover);
	--dplus-bgc-server-button: var(--dplus-dark-bgc-server-button);
	--dplus-bgc-server-button-hover: var(--dplus-dark-bgc-server-button-hover);
	--dplus-bgc-radiobar-hover: hsla(0, 0%, 15%, 0.50);
	--dplus-bgc-radiobar-selected: hsla(0, 0%, 20%, 0.60);
}
.theme-light {
	--dplus-bgc-ui-base: var(--dplus-light-bgc-ui-base);
	--dplus-bgc-ui-base-hover: var(--dplus-light-bgc-base-hover);
	--dplus-bgc-ui-card: var(--dplus-light-bgc-ui-card);
	--dplus-bgc-ui-card-hover: var(--dplus-light-bgc-ui-card-hover);
	--dplus-bgc-chatmsg: var(--dplus-light-bgc-chatmsg);
	--dplus-bgc-chatmsg-hover: var(--dplus-light-bgc-chatmsg-hover);
	--dplus-bgc-popout: var(--dplus-light-bgc-popout);
	--dplus-bgc-button: var(--dplus-light-bgc-button);
	--dplus-bgc-button-hover: var(--dplus-light-bgc-button-hover);
	--dplus-bgc-server-button: var(--dplus-light-bgc-server-button);
	--dplus-bgc-server-button-hover: var(--dplus-light-bgc-server-button-hover);
	--dplus-bgc-radiobar-hover: hsla(0, 0%, 92%, 0.70);
	--dplus-bgc-radiobar-selected: hsla(0, 0%, 80%, 0.60);
}

/* Blur */
:root {
	--dplus-blur-ui: 2px;
	--dplus-blur-popout: 3px;
	--blurcalc-popout: blur(calc(var(--dplus-blur-popout) / 100 * var(--dplus-blur-scale)));
	--blurcalc-ui: blur(calc(var(--dplus-blur-ui) / 100 * var(--dplus-blur-scale)));
}


/* Discord's variables */
body {
	--brand-color: var(--dplus-accent-ui);
	--brand-color-hover:  var(--dplus-accent-ui-hover);
}
.theme-dark, .theme-light {
	--background-primary: var(--dplus-bgc-ui-base) !important;
	--background-secondary: var(--dplus-bgc-ui-card) !important;
	--background-tertiary: transparent !important; /* if this is not transparent, background breaks */
	--background-secondary-alt: transparent ! important; /* bottom-left account details */
	--channelbodyarea-background: transparent !important;
	--background-floating: var(--dplus-bgc-popout) !important;
	--radio-group-dot-foreground: white;
	--brand-experiment: var(--dplus-accent-ui); /* remove the weird new branding colour with a much better accent colour */
}

.theme-dark {
	--bd-blue: var(--dplus-accent-ui) !important;
	--background-accent: var(--dplus-accent-ui);
}

.theme-light {
	--background-secondary:	hsla(0, 0%, 97%, 0.88) !important;
	--header-primary: #060607;
	--header-secondary: #4f5660;
	--text-normal: #000;
	--text-muted: #747f8d;
	--text-link: #0067e0;
  --channels-default: #1f1f1f;
  --interactive-normal: #1f1f1f;
	--interactive-hover: #2e3338;
	--interactive-active: black;
	--interactive-muted: #8f99a3;
	--bd-blue: var(--dplus-accent-ui) !important;
	--background-accent: var(--dplus-accent-ui);
}


/* Quick and dirty fix for create a new server in dark mode */
.theme-dark .layer-2KE1M9 .theme-light { /* the ones i actually need */
	--header-primary: #060607;
	--header-secondary: #4f5660;
	--text-normal: #2e3338;
	--interactive-normal: #4f5660;
}


/* Background image */
#app-mount {
	background: var(--dplus-background) !important;
	background-size: cover !important;
	background-position: center !important;
}
html { background-color: var(--dplus-accent-ui); }


/* Fonts */
	/* Display font */
:root {
	--font-display: var(--dplus-font-ui), 'Poppins', var(--dplus-font-ui-ru), 'Comfortaa', var(--dplus-font-ui-vi), 'Raleway', var(--dplus-font-ui-ja), 'Kosugi',  var(--dplus-font-ui-ko), 'Gothic A1', var(--dplus-font-ui-el), 'Commissioner', '-apple-system', 'Helvetica Neue', 'system-ui', 'Tahoma', 'Segoe UI', 'Helvetica', 'Whitney', sans-serif !important;
	--font-primary: var(--font-display);
	--font-japanese: var(--font-display);
	--font-korean: var(--font-display);
	--font-chinese-simplified: var(--font-display);
	--font-chinese-traditional: var(--font-display);
}
body, button, select {
	font-family: var(--font-display);
}

	/* Text font */
::placeholder, ::-webkit-input-placeholder, p, bodyarea, input, select, textarea,
.message-2qnXI6, .markup-2BOw-j, /*chat messages*/
.subText-1KtqkB, /*member list body*/
.customStatusText-2opeSw, /*user's custom status*/
.modeDefault-3a2Ph1, /*settings small body*/
.emojiInput-1aLNse, .emojiAliasPlaceholder-3H_iZA, /*server settings: emoji name*/
.topic-TCb_qw, /*channel topic in chat header*/
.content-38qMG0, /*channel topic popup body*/
.bd-description /*BD: plugin/theme desc*/ {
	font-family: var(--dplus-font-body), 'Roboto', '-apple-system', 'Helvetica Neue', 'system-ui', 'Arial', 'Helvetica', 'Whitney', sans-serif !important;
}

	/* Names, titles, and headers font */
header, h1,
.nameAndDecorators-5FJ2dg, /*name in member list*/
.headerNameWrapper-3res2c, /*nickname in profile popup*/
.username-1A8OIy, /*username in chat*/
.headerText-15Q25Z, /*username#tag in profile popup*/
.nickname-2gQ76l, /*nickname in profile popup*/
.nameTag-3uD-yy, /*your username in the bottom-left*/
.detailsInner-1VPlWl, /*settings: your username in My Account*/
.activityName-1IaRLn, /*user's activity name, includes song and author titles*/
.emojiUploader-1f0pVx, /*server settings: emoji's uploader*/
.userHook-3AdCBF, /*server settings: username in audit log*/
.secondaryHeader-2oeRPO, /*server settings: integrations row headers such as bot names*/
.roleName-32vpEy, /*role name in profile*/
.roleName-1vjSQR, .roleName-2IkRdr, /*role name in server settings*/
.membersGroup-v9BXpm, /*role name in member list*/
.roleRow-1iQo_1, /*role name in context menu*/
.roleMention-2Bj0ju, /*role name mention in chat*/
.wrapper-3WhCwL, /*username or channel name mention in chat*/
[data-slate-object="inline"] .mention, /*mention in message box*/
.systemMessage-1I9LCe .anchorUnderlineOnHover-2ESHQB, /* links / usernames in system messages */
.name-3l27Hl, /*category name in sidebar*/
.name-23GUGE, /*channel name in sidebar*/
.title-29uC1r, /*channel name in chat header*/
.title-3sZWYQ, /*channel name in channel topic popup*/
.bd-author, .bd-meta .bd-link, /*BD: plugin/theme author*/
.timestamp-3ZCmNB /*chat message hover timestamp (counts as a header)*/ {
	font-family: var(--dplus-font-header), 'Righteous', var(--dplus-font-header-ja), 'RocknRoll One', var(--dplus-font-header-ko), 'Black Han Sans', var(--dplus-font-header-ru), 'Russo One', var(--dplus-font-header-hi), 'Palanquin Dark', var(--dplus-font-header-th), 'Mitr', var(--dplus-font-header-el), 'Alegreya Sans', 'Lalezar', 'Century Gothic', 'Franklin Gothic Medium', 'Britannic', 'Helvetica Neue', 'Helvetica', 'Whitney', sans-serif !important;
}

/* App margins */
.app-2rEoOp, .app-1q1i1E {
	left:		calc(var(--dplus-spacing-app) - 5px) !important;
	top:		calc(var(--dplus-spacing-app) - 5px) !important;
	right:	calc(var(--dplus-spacing-app) + 5px) !important;
	bottom:	calc(var(--dplus-spacing-app) + 5px) !important;
}

/* Loading page (disconnect error) */
.container-16j22k { background-color: hsla(0, 0%, 0%, 0.68) }
.quote-3aooyW {
	font-size: 20px !important;
	margin-bottom: 0px !important;
}
.status-1JTY3j, .problemsText-1Yx-Kl {
	color: white;
	text-transform: none;
	font-size: 16px !important;
}
.attribution-aTC3hS, .links-3Ldd4A {
	font-size: 0px !important;
}
.twitterLink-3NsWMp:before,
.statusLink-gFXhrL:before {
	background-size: 24px 24px;
	height: 24px;
	width: 24px;
}

/* Crash error */
.errorPage-u8SYh4 {
	width: calc(100% - var(--dplus-spacing-app) * 2)
}
.wrapper-1prNyd {
	min-height: calc(100vh - var(--dplus-spacing-app) * 2)
}

.theme-dark .wrapper-1prNyd,
.theme-light .wrapper-1prNyd {
	background: var(--dplus-bgc-ui-base);
	margin: var(--dplus-spacing-app) calc(var(--dplus-spacing-app) * 2) var(--dplus-spacing-app) var(--dplus-spacing-app);
	border-radius: var(--dplus-radius-ui);
}

.theme-dark .image-3zK3Wt,
.theme-light .image-3zK3Wt {
	background-image: url('https://cdn.discordapp.com/attachments/560369937084973067/853659649340473414/28.webp')
}
.image-3zK3Wt {
    width: 256px;
    height: 256px;
    margin-bottom: 40px;
    background-size: 256px 256px;
}

.title-3trS3_,
.note-450gs3 div p {
	font-size: 0px;
}

.title-3trS3_:after {
	font-size: 24px;
	content: "Congratulations!";
}

.note-450gs3 div p:first-child:after {
	font-size: 16px;
	content: "You just unlocked Discord Minus!";
	color: white;
}
.note-450gs3 div p:nth-child(2):after {
	font-size: 16px;
	content: "...actually, Discord just crashed. Oops."
}

/* Scrollbar */
.theme-dark ::-webkit-scrollbar-track-piece,
.theme-dark .theme-light ::-webkit-scrollbar-track-piece,
.theme-light .theme-dark ::-webkit-scrollbar-track-piece {
  background:  hsla(0,0%,0%,0.3)!important;
}
.theme-light ::-webkit-scrollbar-track-piece {
  background:  hsla(0,0%,100%,0.3)!important;
  border: none!important;
}
::-webkit-scrollbar-thumb {
  background: var(--dplus-accent-ui)!important;
  border: none!important;
  border-radius: var(--dplus-radius-ui);
}
::-webkit-scrollbar {
  width: var(--dplus-scrollbar-width) !important;
}
.scroller-2TZvBN::-webkit-scrollbar, .scroller-1Bvpku::-webkit-scrollbar {
	width: 0!important;
}
::-webkit-scrollbar-track {
  background: transparent!important;
  border: none!important;
}


/* Modals */
.root-1gCeng {
	background-color: var(--dplus-bgc-popout) !important;
	border-radius: var(--dplus-radius-ui) !important; 
	backdrop-filter: var(--blurcalc-popout);
}
#app-mount .footer-2gL1pp {
	background-color: transparent;
	box-shadow: none;
}
iframe {
	border-radius: var(--dplus-radius-ui);
}
.modal-yWgWj- {background-color: transparent; box-shadow: none;}
.backdrop-1wrmKB, .backdropWithLayer-3_uhz4 {
	background-color: rgba(0, 0, 0, 0.6) !important;
	backdrop-filter: var(--blurcalc-ui);
}

	/* Create/Join Server Modal */
.theme-dark .theme-light .root-1gCeng {background: var(--dplus-bgc-popout) !important;}
.theme-dark .theme-light .container-UC8Ug1 {background: var(--dplus-bgc-ui-card);}
.filledIcon-2eb7eA { border-radius: var(--dplus-radius-ui); }
.container-UC8Ug1:hover {background: var(--dplus-bgc-ui-card-hover) !important;}
.theme-dark .theme-light {
	--header-primary: #fff;
	--header-secondary: #b9bbbe;
	--text-normal: #dcddde;
	--text-muted: #72767d;
	--text-link: #00b0f4;
	--channels-default: #8e9297;
	--interactive-normal: #b9bbbe;
	--interactive-hover: #dcddde;
	--interactive-active: #fff;
	--interactive-muted: #4f545c;
}
.header-3msK0M {overflow: hidden;}

.optionContainer-15srkc {
	background-color: var(--dplus-bgc-ui-card);
}
.optionContainer-15srkc:hover {
	background-color: var(--dplus-bgc-ui-card-hover);
}

	/* Custom status modal */
.input-cIJ7To.focused-1mmYsC, .input-cIJ7To:focus, .lookFilled-1h1y05.select-1Pkeg4:focus,
.lookFilled-1h1y05.select-1Pkeg4:hover.selectOpen-hQuR6b, .lookFilled-1h1y05.selectOpen-hQuR6b {border-color: var(--dplus-accent-ui);}

	/* Quick switcher modal */
#app-mount .quickswitcher-3JagVE {
	background-color: var(--dplus-bgc-popups);
	box-shadow: none;
	height: 300px;
}
.container-3qKHyN {height: auto;}

	/* Keyboard Combos modal*/
#app-mount .keyboardShortcutsModal-3piNz7 {background-color: transparent;}
#app-mount .keybindShortcut-1BD6Z1 span {background-color: var(--dplus-accent-ui); border-color: black;}

	/* Region select modal */
.regionSelectModal-12e-57 {
	background: transparent;
}
	/* Pin message modal */
#app-mount .message-2qRu38 {
	background-color: var(--dplus-bgc-chatmsg);
	border-radius: var(--dplus-radius-ui);
	border: 1px solid var(--dplus-accent-ui);
	box-shadow: none;
	padding: 0;
	min-height: 70px;
}
	/* Upload modal */
.uploadModal-2ifh8j { background-color: var(--dplus-bgc-ui-base) !important; }
.uploadModal-2ifh8j, #app-mount .footer-3mqk7D {
	border-radius: var(--dplus-radius-ui) !important;
	box-shadow: none;
}
.uploadModal-2ifh8j, .uploadModal-2ifh8j .channelbodyArea-2VhZ6z {	border: 2px dashed var(--dplus-accent-ui); }
.footer-3mqk7D { background-color: var(--dplus-bgc-ui-base) !important; }


/* Popouts */
.layer-v9HyYc > div > div:not(.tooltipPointer-3ZfirK) {
	background-color: var(--dplus-bgc-popout);
	border-radius: var(--dplus-radius-ui);
}

.popouts-2bnG9Z {
    z-index: 1000 !important;
}

	/* Context menu */
.scroller-3BxosC, .submenuPaddingContainer-fiOCHc {
	padding: 0;
}
.scroller-3BxosC::-webkit-scrollbar, .submenuPaddingContainer-fiOCHc::-webkit-scrollbar {
	width: 0 !important;
}
.submenuPaddingContainer-fiOCHc {margin-right: -4px;margin-left: -4px;} /* fixes the submenu being four pixels off */

.labelContainer-1BLJti {
	padding: calc(var(--dplus-spacing-ui) / 1.25) var(--dplus-spacing-ui);
}

.item-1tOPte:not([aria-haspopup="true"]),
.item-1tOPte[aria-haspopup="true"],
.wrapper-3_530D,
.separator-2I32lJ { backdrop-filter: var(--blurcalc-popout) }
/* the context menu backdrop blur has to be applied separately for elements
that have popups, or else the menu breaks when you hover over them */

.wrapper-3_530D { padding: 0; }
.customItem-a8hq58 .button-38aScr { padding: calc(var(--dplus-spacing-ui) / 2); }
.separator-2I32lJ { margin: 0; }

.item-1tOPte,
.button-38aScr {
	border-radius: var(--dplus-radius-ui);
}
.item-1tOPte {
	margin: 0;
	transition: background-color var(--dplus-anim-button);
}

.button-38aScr:not(.lookBlank-3eh9lL):not(.lookLink-9FtZy-):not(.lookOutlined-3sRXeN):not(.colorRed-1TFJan):not(.colorWhite-rEQuAQ), /* non-special buttons */
.colorDefault-2K3EoJ:not(.labelContainer-1BLJti) /* regular buttons, except context menu */ {
	background-color: var(--dplus-bgc-button);
	transition: var(--dplus-anim-button);
}

[id^="status-picker-"] /* status picker (who would've guessed?) */ {
	background-color: transparent !important;
}

.button-38aScr:not(.lookBlank-3eh9lL):not(.lookLink-9FtZy-):not(.lookOutlined-3sRXeN):not(.colorRed-1TFJan):not(.colorWhite-rEQuAQ):hover, /* buttons hovered over */
.button-38aScr.focused-3ZzkKr, /* focused but not hovered over */
.colorDefault-2K3EoJ:not(.labelContainer-1BLJti).focused-3afm-j, /* regular buttons, focused */
.colorDefault-2K3EoJ:hover:not(.labelContainer-1BLJti):not(.hideInteraction-1iHO1O) /* regular buttons but only if clickable */ {
	background-color: var(--dplus-bgc-button-hover);
	transition: var(--dplus-anim-button);
}
.lookFilled-1Gx00P.colorBrand-3pXr91, /* branded buttons */
.labelContainer-1BLJti:hover, /* context menu buttons */
[id^="status-picker-"]:hover /* status picker hovered */  {
	background-color: var(--dplus-accent-ui) !important;
}
.lookFilled-1Gx00P.colorBrand-3pXr91:hover, /* branded buttons, hovered over */
.labelContainer-1BLJti.focused-3afm-j:not(:hover), /* context menu button w/ submenu */
.colorDefault-2K3EoJ:active:not(.hideInteraction-1iHO1O) /* status picker drag-click */ {
	background-color: var(--dplus-accent-ui-hover) !important;
}


.item-1tOPte.colorDanger-2qLCe1:hover {background-color: #f04747;}

	/* Profile Popout */
.root-SR8cQa {
	background-color: transparent;
	backdrop-filter: var(--blurcalc-popout);
}

.headerNormal-1mX3KY,
.body-3HBlXn,
.bodyInnerWrapper-26fQXj {
	background-color: transparent;
}

.headerTop-2cWpdB {
	background-color: var(--dplus-bgc-ui-card);
}

.translate-2dAEQ6,
.popout-2iWAc- {
	backdrop-filter: var(--blurcalc-popout);
}
.userPopout-xaxa6l {
	background-color: var(--dplus-bgc-popout);
	border-radius: var(--dplus-radius-ui);
	box-shadow: none !important;
}

.avatarPositionNormal-aZjAsn {
	left: var(--dplus-spacing-ui);
}

/* this link doesn't do much other than take up space */
.setIdentityLink-1t8Ahd {
	display: none;
}

.customStatus-oN4ZZY {
	padding-top: var(--dplus-spacing-ui)
}

.avatarWrapper-3r9PdD:before {
	content: "";
	position: absolute;
	width: 100%;
	height: 100%;
	z-index: 0;
	background-color: var(--dplus-bgc-ui-card);
	backdrop-filter: var(--blurcalc-ui);
	border-radius: var(--dplus-radius-avatar);
	clip: rect(auto,auto,44px,auto);
}

.avatar-37jOim {
	border-width: 6px;
	border-style: solid;
	border-color: transparent;
	border-radius: var(--dplus-radius-ui);
	background-color: transparent;
}

.userPopout-xaxa6l .wrapper-3t9DeA:not(.baseAvatar-3Nvk7n),
.container-3RCQyg .wrapper-3t9DeA,
.avatarUploaderInner-2EvNMg,
.avatarHint-2A3RNb {
	width: var(--dplus-icon-avatar-profile) !important;
	height: var(--dplus-icon-avatar-profile) !important;
}

.assetsLargeImage-eYwpTX {
	border-radius: var(--dplus-radius-ui);
}

	/* Profile modal */
.avatar-AvHqJA {
	width: calc(var(--dplus-icon-avatar-profile) * 1.5) !important;
	height: calc(var(--dplus-icon-avatar-profile) * 1.5) !important;
	border-radius: var(--dplus-radius-avatar);
	border-width: 8px;
	border-style: solid;
	border-color: transparent;
	background-color: transparent;
}

.avatar-AvHqJA:before {
	content: "";
	position: absolute;
	width: 100%;
	height: 100%;
	right: -8px;
	top: -8px;
	border-width: 8px;
	border-style: solid;
	border-color: transparent;
	background-color: var(--dplus-bgc-popout);
	border-radius: calc(var(--dplus-radius-avatar) + 5px);
	clip: rect(auto,auto,68px,auto);
}

.top-28JiJ- .item-PXvHYJ {
	border-radius: 0 !important;
}

.listRow-hutiT_ {
margin: var(--dplus-spacing-ui);
padding: var(--dplus-spacing-ui);
}
.listRow-hutiT_ .iconInactive-98JN5i {
	border-radius: var(--dplus-radius-server);
	width: var(--dplus-icon-server-list);
	height: var(--dplus-icon-server-list);
}
.listAvatar-1NlAhb {
	margin-right: var(--dplus-spacing-ui);
}
.body-r6_QPy, .topSection-y3p-_D {
	background-color: transparent;
}

.aboutMeSection---MkQa {
	background-color: transparent;
}

.nickname-322DbL {
	font-family: inherit;
}

.disabledButtonWrapper-3wH6-b { display: none; /* Remove Spotify buttons for yourself */ }
.button-2IFFQ4 { margin-top: var(--dplus-spacing-ui); }

[style="background-color: rgb(114, 137, 218);"] {
	background-color: var(--dplus-accent-ui) !important;
}
.theme-dark .path-92Hmty,
.theme-light .path-92Hmty {
    stroke: var(--dplus-accent-ui) !important;
}

.activity-fViXj7 {
	border-bottom: 0;
}

	/* Roles */
.role-2irmRk {
	border-radius: var(--dplus-radius-ui);
	position: relative;
	overflow: hidden;
}
.roleCircle-3xAZ1j::after {
	content: "";
	background: inherit;
	height: 24px; width: 100%;
	position: absolute;
	left: 0;
	opacity: 0.72;
	z-index: -1;
}

	/* Tooltips */
.tooltip-2QfLtc {
	backdrop-filter: var(--blurcalc-popout);
}
.tooltipContent-bqVLWK {
	padding: var(--dplus-spacing-ui);
	background-color: transparent !important;
}

	/* Search */
.search-2oPWTC .searchBar-3dMhjb {
	transition-duration: var(--dplus-anim-short);
}
#app-mount .container-3ayLPN {
	background-color: var(--dplus-bgc-popout);
	border-radius: var(--dplus-radius-ui);
	width: 404px!important;
	margin-left: -68px;
}
#app-mount .option-96V44q.selected-rZcOL- {
	background-color: var(--dplus-accent-ui);
	border-radius: var(--dplus-radius-ui);
}
#app-mount .searchAnswer-3Dz2-q, #app-mount .searchFilter-2ESiM3,  #app-mount .jumpButton-JkYoYK {
	background-color: var(--dplus-accent-ui)!important;
	color: white;
}
.channelName-1JRO3C {
	background: var(--dplus-accent-ui);
	color: white;
	border-radius: var(--dplus-radius-ui);
	padding: 8px;
	opacity: 0.6;
}
.content-1x5b-n {
	margin-left: 0;
	margin: 0 var(--dplus-spacing-ui);
	padding: 0 calc(var(--dplus-spacing-ui) / 2);
	border-radius: var(--dplus-radius-ui);
}
.channelSeparator-1DOiGt:before {
	background-color: var(--dplus-accent-ui);
	opacity: 0.3;
}
.searchResult-9tQ1uo.expanded-w_LCGl {
	border: 1px solid var(--dplus-accent-ui) !important;
	border-radius: var(--dplus-radius-ui) !important;
}
.searchResultMessage-1fxgXh, #app-mount .
