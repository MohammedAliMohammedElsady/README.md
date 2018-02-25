# https-github.com-users-MohammedAliMohammedElsady-emails-46794483-confirm_verification-29a297484c92




1- first, depend on GoogleMapAppi
  1.1 Constructor creates a new map - only center and zoom are required by function initMap() .
  1.2 Creates Markers For map , and marker is object constructor by google.maps.Marker -- contain properties is must ,optional for Example Location ,title ,map 
  1.3 Create Information Window For each  Marker by google.maps.InfoWindow .
 

2- framework knockout is library in javascript for Handle interaction between user(interface-->DOM) && data in dynamic (binding 
datamodel ---> ViewModel)(runTime).
   2.2 most important function in knockout is ko.observable -- do set data && retrieve data from datamodel to viewModel ,
   ko.computed ---> happend when any data is changed in runTime,
   ko.applyBindings  -- > Bind ViewModel && Run Models

3- Get Data From APPI (FourSquare) : retrieve data From APPI FourSquare by ajax .
   3.1 Build your first app using the Places API with this step-by-step guide.
     **Getting Started**
       3.1.1 Setup Your Developer Account
             Thanks for choosing the Places API to build location-based experiences into your app or website. We know that getting 
             started with a new API can be challenging, so we’ve created a step-by-step guide that walks you through how to create a 
             Foursquare Developer account, make your first API call and more.
       3.1.2 Register as a Developer
             If you are an existing Foursquare user, you will be able to use your own account to register. If not, you will have to 
             either Sign Up for Foursquare or login using Facebook.
       3.1.3 Create A New Foursquare App
             On the next page, choose a name for your app and enter the URL where it will be hosted

       3.1.4 Choose Your Account Tier
             After picking a name for your app, select the appropriate tier for your application.
       3.1.5 Obtain Your Client ID and Secret Key
             Once you’ve created your app, make note of your client ID and secret key, as we will need this in the next step. Please 
             note the key below has been generated for this guide and will not be usable in an application.
             //clientID='FPU0LB53TA40FZZ3AS4QYJDD2PMKGTSKFIW14E2WEG4NJ5XA' , 
             clientSecret='JJ1T3GSSVG2GGUGBTWFQ5MLXDAIUWFRGECIFQB4EBJQZHYVK' .
       3.1.6 Make Your First API Call
             Using the client ID and secret obtained previously, lets make our first API call!. The examples below show you how to fi 
             a coffee shop near a given location
 
