# cPanel API PHP Class

This is an obsolete package for interacting with the cPanel & WHM API.  It is no
longer updated.

As of version 74, the XML serialization is no longer available in cPanel & WHM.
However, despite the name of this package and the fact that it is obsolete, it
should be possible to use this package with the JSON serialization (and only the
JSON serialization) in version 74 and newer.


## Installation
 
 1. Append a repository to your composer.json
	
	 	{
            "repositories": [
                {
                "type": "github",
                "url":  "https://github.com/CpanelInc/xmlapi-php.git"
                }
            ]
        }
        	
 1.  Setup package
 
 			composer require 'CpanelInc/xmlapi-php:dev-master'

