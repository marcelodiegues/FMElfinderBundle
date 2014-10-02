FMElfinderBundle
================

[ElFinder](https://github.com/Studio-42/elFinder) integration in Symfony2

[![Build Status](https://secure.travis-ci.org/helios-ag/FMElfinderBundle.png)](http://travis-ci.org/helios-ag/FMElfinderBundle)

[![Total Downloads](https://poser.pugx.org/helios-ag/fm-elfinder-bundle/d/total.png)](https://packagist.org/packages/helios-ag/fm-elfinder-bundle)

[![Latest Stable Version](https://poser.pugx.org/helios-ag/fm-elfinder-bundle/version.png)](https://packagist.org/packages/helios-ag/fm-elfinder-bundle)


elFinder is an open-source file manager for web, written in JavaScript using jQuery UI.
Creation is inspired by simplicity and convenience of Finder program used in Mac OS X operating system.

- [FMElfinderBundle](#fmelfinderbundle)
	- [Installation](#installation)
		- [Step 1: Installation](#step-1-installation)
		- [Step 2: Enable the bundle](#step-2-enable-the-bundle)
		- [Step 3: Import FMElfinderBundle routing file](#step-3-import-fmelfinderbundle-routing-file)
		- [Step 4: Configure your application's security.yml](#step-4-configure-your-applications-securityyml)
		- [Step 5: Configure assetic](#step-5-configure-assetic)
		- [Step 6: Install and dump assets](#step-6-install-and-dump-assets)
	- [Basic configuration](#basic-configuration)
		- [Add configuration options to your config.yml](#add-configuration-options-to-your-configyml)
	- [Configuring symfony service as a volumeDriver](#configuring-symfony-service-as-a-volumedriver)
	- [Using ElFinder with CKEditorBundle](#using-elfinder-with-ckeditorbundle)
		- [Step 1: Installation:](#step-1-installation-1)
		- [Step 2: Configure CKEditor setting via settings.yml or through form builder:](#step-2-configure-ckeditor-setting-via-settingsyml-or-through-form-builder)
	- [Using ElFinder with TinyMCE](#using-elfinder-with-tinymce)
	    - [Using ElfinderBundle with TinyMCEBundle](#using-elfinderbundle-with-tinymcebundle)
		- [Integrating with TinyMCE 4.x](#integrating-with-tinymce-4x)

## Installation

To install this bundle, you'll need both the lib [ElFinderPHP](https://github.com/helios-ag/ElFinderPHP)
and this bundle.

This instruction explain how to setup bundle on Symfony 2.1 and newer

### Step 1: Installation

Add FMElfinderBundle in your composer.json:

```js
{
    "require": {
        "marcelo-diegues/fm-elfinder-bundle": "dev-master"
    }
}
```

To setup the rest of bundle, search about FMElfinderBundle

