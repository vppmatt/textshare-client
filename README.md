# textshare-client

This is the client for the textshare application, a small program which can be installed on virtual machines, and will allow the trainer to provide you with text that can then easily be copied.

## To install this application:

If you do not already have the application on your virtual machine, simply download the jar file from here:
<https://multicode.uk/textshare>.

## To run the application

Just double click the textshare-client file to run the application.

### Setting the font size
By default the application has a font-size of 12. This can be changed by running the application from the 
command line and entering a command line argument. For example, to run the application with a font size of 16, enter:

```java -jar textshare-client.jar -fontsize 16```

### Specifying the training group name

When the application runs, you'll be provided with a list of all the active training groups. Simply select your group 
from the list. If you accidently select the wrong group, just close the application and start again.

If you already know the name of the group you can specify this using a command line argument. For example, to
run the applicaiton and join the gropu called fullstack1, you can enter:

```java -jar textshare-client.jar -group fullstack1```

Note: This option is only available if there are no spaces in the group name.
