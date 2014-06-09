# phpBB Extensions Repository

This repository is a database of phpBB Extensions installable through [phpBB Extensions Manager](https://github.com/carlo94it/phpbb-extensions-manager).

## Add your extensions

If you would add your extensions to our database, please follow the following guidelines:
* Fork the repository
* Create a directory if not exists with your vendor name (eg. carlo94it)
* Create a file called extension-name.json (eg. phpbbextmanager.json) as specified below
* Submit a [pull-request](https://github.com/carlo94it/phpbb-extensions-repository/pulls)

## JSON example for extensions

```json
{
	"name": "vendor/extension-name",
	"display-name": "Extension name",
	"description": "Extension description",
	"version": "1.0.0",
	"download": {
		"url": "vendor/extension-name",
		"type": "github"
	},
}
```

## Downloading methods

Currently the only methods for downloading are:
* github (URL: username/repository-name)
