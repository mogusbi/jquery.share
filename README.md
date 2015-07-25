# jQuery Share plugin
> Resize a textarea as you type.

## Getting started
### NPM
Install package with NPM and add it to your dependencies:  
`npm install @mogusbi/jquery.share --save`

## Introducing it to your page
Include jQuery and the plugin to your page. Ensure you have your canonical and/or short link meta tags present as they will be used to generate the share link

```html
<!doctype html>
<html>
	<head>
		<link href="http://mogusbi.co.uk" rel="canonical" />
		<link href="http://short.link" rel="shortlink" />
	</head>
	<body>
		<button type="button" data-share="facebook">Facebook</button>
		<button type="button" data-share="twitter">Twitter</button>
		<button type="button" data-share="google-plus">Google+</button>
		<button type="button" data-share="whatsapp">Whatsapp</button>
		
		<script src="jquery.js"></script>
		<script src="jquery.share.js"></script>
		<script>
			$('[data-share]').share();
		</script>
	</body>
</html>
```

## License
Copyright &copy; Mo Gusbi.  
Licensed under the MIT license.