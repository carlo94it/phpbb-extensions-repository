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
	"download": {
		"url": "https://github.com/vendor/extension-name.git",
		"version": "master",
		"type": "git"
	}
}
```

## Downloading methods

Currently the only methods for downloading are:
* git (URL: repository url, VERSION: branch/tag name)
