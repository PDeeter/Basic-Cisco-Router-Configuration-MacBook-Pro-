# Basic-Cisco-Router-Configuration-MacBook-Pro-

Basic Setup of a Cisco 1841 Router with Encrypted Password and Configuring VLAN's and Interfaces

The connection of this Router to the Macbook Pro has been connected from the console port of the router to a USB-C port on the Macbook using a Ethernet-USB A Console cable with a USB-A to USB-C adapter.

Step 1: Find the name of the Serial Port of the Router.

Once you have connected the router and Macbook via console cable, you must find the serial port number

- Open a new Terminal Window

- Type in the command: "ls -l /dev/tty.*" to view all of your ports.

<img width="628" height="497" alt="Screenshot 2026-10-11 at 5 09 41 PM" src="https://github.com/user-attachments/assets/0b304940-56a4-4ffd-8c46-c63ec887b482" />

Your Cisco router should fall under the format /dev/tty.usbserial-XXXXXXX

Now, screen into the console using screen /dev/tty.usbserial-XXXXXXX 9600.

This should allow you to access the Command Line of the Router.

<img width="709" height="497" alt="Screenshot 2026-10-11 at 5 17 55 PM" src="https://github.com/user-attachments/assets/ed036b82-5952-44ee-b3bf-5b15abeb5b68" />

And you should get a blank screen. Hit enter a couple times to get this.

<img width="709" height="497" alt="Screenshot 2026-10-11 at 5 19 10 PM" src="https://github.com/user-attachments/assets/5e4a0b20-8be8-4851-add7-7ebbfd71408c" />







