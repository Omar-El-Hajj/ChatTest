<html>
<body>
<script type='text/javascript'>
	function initEmbeddedMessaging() {
		try {
			embeddedservice_bootstrap.settings.language = 'pt_BR'; // For example, enter 'en' or 'en-US'

			embeddedservice_bootstrap.init(
				'00D890000011U8L',
				'PattiWeb',
				'https://pottencialseg--potterdev.sandbox.my.site.com/ESWPattiWeb1707415013331',
				{
					scrt2URL: 'https://pottencialseg--potterdev.sandbox.my.salesforce-scrt.com'
				}
			);
		} catch (err) {
			console.error('Error loading Embedded Messaging: ', err);
		}
	};
</script>
<script type='text/javascript' src='https://pottencialseg--potterdev.sandbox.my.site.com/ESWPattiWeb1707415013331/assets/js/bootstrap.min.js' onload='initEmbeddedMessaging()'></script>

</body>
</html>
