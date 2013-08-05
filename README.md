CsnUser
=======

**What is CsnUser?**

CsnUser is a Module for Authentication based on DoctrineORMModule

**What exactly does CsnUser?**

CsnUser has been created with educational purposes to demonstrate how Authentication can be done. It is fully functional.

**What's the use again?**

Nothing but yet another Authentication Module like ZfcUser.

Installation
============

Installation via composer is supported, simply add the following line to your ```composer.json```

```
"repositories": [
	{
		"type": "vcs",
		"url": "https://github.com/coolcsn/CsnUser"
	}
],
"require" : {
    "coolcsn/csn-user": "dev-master"
}
```

After adding to the composer's packagist.org (not ready yet)

```
"require" : {
    "coolcsn/csn-user": "dev-master"
}
```

An example application configuration could look like the following:

```
'modules' => array(
    'Application',
    'DoctrineModule',
    'DoctrineORMModule',
    'CsnUser'
)
```

Configuration
=============

This Module doesn't require any special configuration. All that's needed is to set up a Connection for Doctrine.

Dependencies
============

This Module depends on the following Modules:

 - DoctrineORMModule
