# WeatherReportingChallenge
Built with the intent to support an internal website, this API is designed to provide real-time data.  It's /weatherReport endpoint uses the client's IP to produce a current forecast for the office location in their state.


To run this locally, you will need to create an account with the following services and fill out the local-config file accordingly:

 - https://anypoint.mulesoft.com/exchange/portals/academymortgage-6/f6ed7e6b-a8a7-4399-beb6-4ef1356423e0/hrdataapi/ 
   - Request access to this API by registering an application to obtain a ClientId and ClientSecret
 - https://ipinfo.io/
   - Create an account and you'll be provided a non-expiring token
 - https://www.weatherapi.com/
   - Sign up.  It will give a free trial, but won't require setting up any kind of subscription as of time of writing this
   
If you are simply interested in trying out this API, you can request access here: https://anypoint.mulesoft.com/exchange/portals/academymortgage-6/f6ed7e6b-a8a7-4399-beb6-4ef1356423e0/weatherreportingchallenge/
