---
title: Interactive API documentation
permalink: /docs/openapi/
---
<style type="text/css" rel="stylesheet">
	.swagger-ui pre {
		background-color: transparent;
		border: none;
	}
</style>

The interactive documentation below demonstrates the functionality of the SWC
Fantasy Football API. To download the OpenAPI Specification (OAS) file, use the
"openapi.json" link below.
<div id="swagger-ui" class="intrinsic-container"></div>
<script src="https://unpkg.com/swagger-ui-dist@5.10.0/swagger-ui-bundle.js" crossorigin></script>
<script>
	window.onload = () => {
		window.ui = SwaggerUIBundle({
			url: '/dev-portal/openapi.json',
			dom_id: '#swagger-ui',
			supportedSubmitMethods: []
		});
	};
</script>
