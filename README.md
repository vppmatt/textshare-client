# textshare-client

This is the client for the textshare application, a small program which can be installed on virtual machines, and will allow the trainer to provide you with text that can then easily be copied.

**To install this application to the virtual machine:**

(1) On the virtual machine, open a command prompt (click on the search icon / magnifying glass, type in CMD, then press enter).

(2) enter the following commands:

cd \workspace

git clone https://github.com/vppmatt/textshare-client.git

**To run the application**

Just locate the textshare-client folder and double click on the file called textshare-client, or to run it with a different default font size try:
java -jar textshare-client.jar -fontsize xx

The default font size is 12

You can specify the group name if it has no spaces in it as a command line argument if known too, e.g.

java -jar textshare-client.jar -group FullStack -fontsize 12
