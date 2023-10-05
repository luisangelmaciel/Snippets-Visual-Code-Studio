# Snippets-Visual-Code-Studio
Shortcuts Snippets Visual Code Studio CSS, HTML, JS

This is a collaction of favorites shorcuts snippets in Visual Code Studio in CSS, HTML, JS


<pre>
{	
	"span lang es": {
		"prefix": "langes",
		"body":[
			"&#60;span lang=es>&#60;/span>"
		],
			"description":"Importat word different lenguage Spanish"},
	"schema software": {
			"prefix": "scriptSchemaApplication",
			"body":[
					"&#60;script type='application/ld+json'>""    {""      '@context': 'https://schema.org',""      '@type': 'SoftwareApplication',""      'name': 'Dino Chrome and friends',""      'url': 'https://www.xbr.pw/game/dinosaur-game-google-chrome/index.html',""      'description': 'El Dino de Google Chrome con sus amigos Goku, Los minion, Iron man y más',""      'operatingSystem': 'ANDROID',""      'applicationCategory': 'GAME',""      'image': 'https://www.xbr.pw/game/dinosaur-game-google-chrome.webp',""      'contentRating': 'Teen',""      'author': {""        '@type': 'Person',""        'name': 'xbr Apps',""        'url': 'http://www.xbr.pw'""      },""      'aggregateRating': {""        '@type': 'AggregateRating',""        'ratingValue': '5',""        'ratingCount': '10'""      },""      'offers': [{""        '@type': 'Offer',""        'price': '0',""        'priceCurrency': 'MXN',""        'availability': 'https://schema.org/InStock'""      }]""    }""  &#60;/script>    "
				   ],
			"description":"SoftwareApplication Android + Rating"},	
	"head schema website":{
			"prefix":"headSchemaWebsite",
			"body":[
				"&#60;head itemscope itemtype='https://schema.org/WebSite'>""    &#60;link rel='stylesheet' type='text/css' href='' media='all'>""&#60;/head>",
			],
			"description":"head con schema microdata website"},
	"sr-only":{
		"prefix":"sr-only",
		"body":[
			"&#60;style>.sr-only {clip: rect(0, 0, 0, 0);border-width:0;height: 1px;margin: -1px;overflow: hidden;padding: 0;position: absolute;white-space: nowrap;width: 1px;}&#60;/style>",
		],
		"description":"No display in the viewport principal but yes reading in the web"},
	"header schema organization":{
			"prefix":"headerSchemaOrganization",
			"body":[
				"&#60;header>&#60;style>.sr-only {clip: rect(0, 0, 0, 0);border-width:0;height: 1px;margin: -1px;overflow: hidden;padding: 0;position: absolute;white-space: nowrap;width: 1px;}&#60;/style>""    &#60;div itemscope itemtype='http://schema.org/Organization' id='schemaOrganization'>""       &#60;a href='#Organization'  aria-label='View source the site' target='_blank' itemprop='url'>""        &#60;span class='sr-only' itemprop='name'>Octo Desing by Luis Angel Maciel&#60;/span>""        &#60;span class='sr-only' itemprop='description'>Made with love and mucho &#60;span lang='es'>código&#60;/span> by Luis Angel Maciel&#60;/span>""        &#60;img class='sr-only' itemprop='logo' aria-label='Logo' arialabelledby='schemaOrganization' alt='Logo' width='100%' height='auto' src='https://luisangelmaciel.github.io/img//lamp-loader.svg'>""       &#60;/a>""    &#60;/div>""&#60;/header>",
			],
			"description":"Header sr only con schema microdata organization"},
	"html body center":{
		"prefix":"htmlBodyCenter",
		"body":[
			"&#60;style>html, body {width: 100vw;height: 100vh;margin: 0;padding: 0;}body {display: flex;flex-direction: row;justify-content: center;align-items: center;}&#60;/style>",
		],
		"description":"Content center"}
}	
</pre>

## Install 
### Option 1 
Download  file <a href="./html.json">html.json</a>

### Option 2
Copy and paste in your Visual Code Studio 

##### Fork, start, donate & love in
<a href="https://codepen.io/luisangelmaciel/pen/KKbGJRz">Codepen</a> | <a href="https://github.com/luisangelmaciel/Snippets-Visual-Code-Studio">Github</a>
