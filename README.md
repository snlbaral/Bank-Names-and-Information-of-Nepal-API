Response Format: JSON Encoded

Endpoint URLs:
		https://jcloudia.com/api/banks/commercial
		https://jcloudia.com/api/banks/developments

Usage: 

https://jcloudia.com/api/banks/commercial/{?OPTIONAL}
	{OPTIONAL}:
		'list_by': {PARAMETERS}
				'name',
				'operational_date',
				'paidup_capital',


Example:

https://jcloudia.com/api/banks/commercial
https://jcloudia.com/api/banks/commercial/?list_by=paidup_capital
