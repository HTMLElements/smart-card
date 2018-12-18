[![Published on webcomponents.org](https://img.shields.io/badge/webcomponents.org-published-blue.svg)](https://www.webcomponents.org/element/htmlelements/smart-card)

# &lt;smart-card&gt;

[Live Demo ↗](https://htmlelements.com/demos/card/)
|
[Documentation ↗](https://www.htmlelements.com/docs/)
|
[Installation ↗](https://www.npmjs.com/package/@smarthtmlelements/smarthtmlelements-core)

[&lt;smart-card&gt;](https://htmlelements.com/demos/card/) is a Custom HTML Element providing Card view with HTML Content](https://htmlelements.com/).

<!--
```
<custom-element-demo>
  <template>
    <script src="../webcomponentsjs/webcomponents-lite.js"></script>
    <script src="../smart-core/source/smart.core.js"></script>
    <link rel="stylesheet" href="../smart-core/source/styles/smart.default.css" type="text/css" />
	<style>
		body {
			margin: 0px;
			padding: 0px;
		}

		smart-card.basic-card .card-content,
		smart-card.basic-card .card-action {
			box-sizing: border-box;
			padding: 20px;
			color: white;
			background-color: #546E7A;
			border-bottom: 1px solid rgba(160,160,160,0.2);
			border-radius: 2px 2px 2px 2px;
		}

		smart-card.basic-card .card-title {
			font-size: 18px;
		}

		smart-card.basic-card a {
			color: #ffab40;
			transition: color .3s ease;
			text-transform: uppercase;
			border-bottom: none;
			text-decoration: none;
			margin-right: 20px;
		}

			smart-card.basic-card a:hover {
				color: #ffd8a6;
			}
	</style>
     <next-code-block></next-code-block>
  </template>
</custom-element-demo>
```
-->
```html
   <smart-card class="basic-card">
        <div class="card-content">
            <span class="card-title">Card Title</span>
            <p>
                I am a very simple card. I am good at containing small bits of information.
                I am convenient because I require little markup to use effectively.
            </p>
        </div>
        <div class="card-action">
            <a href="#">This is a link</a>
            <a href="#">This is a link</a>
        </div>
    </smart-card>
```

[<img src="https://raw.githubusercontent.com/htmlelements/smart-card/master/smart-card-web-component.png" alt="Screenshot of smart-card">](https://htmlelements.com/demos/card/)

## Getting Started

Smart HTML Elements components documentation includes getting started, customization and api documentation topics.

[Getting Started Documentation](https://www.htmlelements.com/docs/)


## The file structure for Smart HTML Elements

- `source/`

  Javascript files.

- `source/styles/`

  Component CSS Files.

- `demos/`

  Demo files

## Running demos in browser

1. Fork the `Smart-HTML-Elements-Core` repository and clone it locally.

1. Make sure you have [npm](https://www.npmjs.com/) installed.

1. When in the `Smart-HTML-Elements-Core` directory, run `npm install` and then `bower install` to install dependencies.

1. Run a localhost or upload the demo on a web server. Then run:

  - /demos/smart-card/smart-card-overview.htm


## Following the coding style

We are using [ESLint](http://eslint.org/) for linting JavaScript code. 

## Creating a pull request

  - Make sure your code is compliant with ESLint
  - [Submit a pull request](https://www.digitalocean.com/community/tutorials/how-to-create-a-pull-request-on-github) with detailed title and description
  - Wait for response from one of our team members


## License

Apache License 2.0
