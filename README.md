# Whiteness - A sample Magento Theme

A Magento theme that is just the homepage, used for a .net Magazine tutorial

## Installation

You have two options:

### Manual

Copy the <code>app/design/frontend/dotnet</code> and <code>skin/frontend/dotnet</code> into the <code>app/</code> and <code>skin/</code> folders in your Magento installation.

### Using the Ant Buildfile

* Install [Ant](http://ant.apache.org/manual/install.html)
* Copy <code>build.default.properties.example</code> to <code>build.default.properties</code> and then edit the <code>deploy.dir</code> to point to the root folder of a  Magento installation on your local machine.
* Then from the same directory as <code>build.default.properties</code> run <code>ant build</code>. This will copy all the module files into your Magento installation and enables them.
* Clear Magento cache and refresh the page

## Enable the theme

In the Magento admin, go 'System' >> 'Configuration' >> 'Design' >> 'Package'. Enter ‘dotnet’ for the package name and then ‘whiteness’ for templates, skin and layout and put ‘default’ in the default field. Then Save.