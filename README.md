# Very basic oauth tutorial

The index.html file is well commented, so you should be able to get all the
informaiton from there.  We will be following the "Implicit" flow, which
means only one round-trip to the facebook server.

You can see the code in action by visiting
[https://env3d.github.io/oauth-basic-tutorial/](https://env3d.github.io/oauth-basic-tutorial/)

# Setup facebook app

If you want to deploy this example to your own site, you'll need to create your own
facebook app.  This is because each app only allow a restricted set of redirect_uri.

Visit [https://developer.facebook.com/](https://developer.facebook.com/) to create a
new app, then make sure you set the following parameters in the developer console.

## Under "Basic" 

![Basic Settings](basic_settings.png)

## Under "Facebook Login"

![Login Settings](login_settings.png)