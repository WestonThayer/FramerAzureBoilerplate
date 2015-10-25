# Framer Azure Boilerplate

Boilerplate files for hosting FramerJs prototypes in Azure Websites (or any IIS server). Mostly copied from [Fernando Correia](https://github.com/fernandoacorreia)'s [StaticAuthSample](https://github.com/fernandoacorreia/StaticAuthSample).

## Usage

1. [Download](https://github.com/WestonThayer/FramerAzureBoilerplate/archive/master.zip) and unzip
2. Copy the contents of your `MyPrototype.framer/` folder into the `PrivatePrototype/` folder
3. Copy `Web.config`, `Login.aspx`, and the `PrivatePrototype/` folder over to your Azure Website. [WebMatrix](http://www.microsoft.com/web/webmatrix/) makes this easy
4. Visit `http://YOUR_SITE.azurewebsites.net/PrivatePrototype/` and enter `Alice` as the user and `secret` as the password to log in

## Tweaks

### Change the `PrivatePrototype/` URL

Just change the folder name.

### Change the username and password

Open the root `Web.config` and read the comments.

### Add another private prototype

Create a new folder, copy `PrivatePrototype/Web.config` to it, then your Framer Studio files.

### Add a public prototype

Create a new folder and copy your Framer Studio files.