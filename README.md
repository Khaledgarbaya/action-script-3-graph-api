Actionscript 3.0 graph api ( Coming SOON)
==========================

an updated version of the  https://code.google.com/p/facebook-actionscript-api/ to work with Facebook Graph API 2.0

I added the version support and by that I fixed the graph api URL so the new one will be 
https://graph.facebook.com/v2.0/

Sample Code
-----------
    Facebook.init(applicationId,
              callback,
              {version:"2.0"},
		      accessToken
    );//if you don't specify the version , 2.0 will be the default value
