# IOT-Light-tutorial

This uses Thingspeak as the IOT cloud. To begin with login to Thingspeak with the credentials and then create a new channel.Once a new channel is created.Click on the "Create" option on the top and select "+" symbol.Now choose the "Google Voice Assistant" option. Fill in all the credentials needed.Now we will be redirected to the "IF THIS THEN THAT" webpage.Now choose the other "+" symbol and use "WEBHOOKS" service.Fill in the credentials.Repeat the same thing for the "off" service as well.

Now the webservice is setup.The next thing we have to do is,program the microcontroller we are using which is NodeMCU ESP8266 module.The coding is done in the arduino IDE.But we can use drag and drop platform and then generate the code from there and dump it into the microcontroller using the arduino IDE.

Here is a sample:
![Tuniot.tn](https://github.com/shreyan1999/IOT-Light-tutorial/blob/master/github.png)

Visit this website to create your own code! [TUNIOT](http://easycoding.tn/tuniot/demos/code/).

Install necessary libraries in your Arduino IDE before compiling the code to avoid errors while uploading it to the board.

Now we are all set! "Okay Google! Turn on the light" 
