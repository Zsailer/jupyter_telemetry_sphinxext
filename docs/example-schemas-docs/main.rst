.. jupyter_telemetry_schema::

	{
	    "$id": "url.to.event.schema",
	    "version": 1,
	    "title": "My Base Event",
	    "description": "All events must have a name property\n",
	    "type": "object",
	    "properties": {
	        "name": {
	            "title": "Name",
	            "description": "Name of event\n",
	            "type": "string"
	        }
	    },
	    "required": [
	        "name"
	    ]
	}