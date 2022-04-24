# Covid19-app-exposure
This code project uses the Exposure Notification framework to build a sample app that demonstrates how to notify people when they have come into contact with someone who meets a set of criteria for a case of COVID-19. When using the project as a reference for designing an Exposure Notifications app, you can define the criteria for how the framework determines whether the risk is high enough to report to the user.  The sample app includes code to simulate server responses. When building an Exposure Notifications app based on this project, create a server environment to provide diagnosis keys and exposure criteria, and add code to your app to communicate with this server. If the app you build operates in a country that authenticates medical tests for COVID-19, you may need to include additional network code to communicate with those authentication services.