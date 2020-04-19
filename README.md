# .varl (VARiable List) v1.0.0  
  
The simplest way to transfer data or store as configuration file.  
  
## How to use?  
  
**Simple.** This is the example:  

    * This is a .varl formatted file, let's call it configuration.varl :)

    server name = varl.org
    maintainer  = Athaariq Ardhiansyah
    host        = 127.0.0.1
    port        = [80, 443]
    daemonize   = true
    SSL Cert    = /home/secrets/bundle.cert
    
    routes = {
	    home   = /
	    login  = /auth/login
	    signup = /auth/register
	}
  
If you convert configuration.varl into JSON:

    {
	    "server name" : "varl.org",
	    "maintainer" : "Athaariq Ardhiansyah",
	    "host" : "127.0.0.1",
	    "port" : [80, 443],
	    "daemonize" : true,
	    "SSL Cert" : "/home/secrets/bundle.cert",
	    "routes" : {
		    "home" : "/",
		    "login" : "/auth/login",
		    "signup" : "/auth/register"
		}
	}

**Interested?** [Learn more here](https://github.com/Thor-x86/varl/blob/master/docs/1-Getting_Started.md)  
  
## What the difference?

In .varl, simplicity is the main goal. Therefore:  

- No excess mandatory characters as example root bracket "{ }" and commas on JSON. The cool thing is you're not always require double quote to mark the string, the .varl decoder will automatically detect every standard data type.
- Doesn't require malicious structure such as dictionary, collection, tables, etc. Just key and value pairs with array and object compatible. Keep it simple!
- Unlike .ini format, the .varl format is standardized. That's why this documentation repository is created.
  
## How to implement?  
  
- JavaScript: [varl-js](https://github.com/Thor-x86/varl-js)  

Contributors are welcome to adopt on any programming language :)  

## How do I contribute?
  
We have documented how to properly contribute [at here](https://github.com/Thor-x86/varl/blob/master/docs/5-contribution.md).  