

I'd like to explain how to register a nickname (acount) in IRC channels. It's 
easy.

1. Choose a Messenger that support [IRC Protocol][IRC Protocol]

There is several softwares that do the job, so you'll have to find by your own.
This tutorial was based on the use of [Pidgin][Pidgin].

2. Create a NickName within the Messenger of your choice

In the IRC protocol, each user has a unique nickname that serves as a identifyer.
So, now is the time for you think about a cool nickname for you self. Mine is 
'yasj'. If a nickname is already registered, the server will notify you that 
(which will make feel sad). So, let's do it:

    1. Open pidgin, and choose the option 'Account>Manage Accounts' [Ctrl+A]
    2. Click in 'Add' button
    3. In the Protocol, choose 'IRC'
    4. Pickup a username and a unguessable password of your choice
        When finished, click in 'Add' and wait. A window named 'NickServ' will 
        be opened.
    5. Register your nickname in freenode server
        In the NickServ window, type the following command

            /msg NickServ REGISTER <passwd> <email>

        where:
            <passwd> is the password that you selected
            <email> an email for the registration

        So, in the same window, the server will response the following message:
        An email containing nickname activation instructions has been sent 
        to <your email>.
        (notice) If you do not complete registration within one day, your 
         nickname will expire.
        (notice) IRCTEST123 is now registered to <your email>, with the 
         password <your password>.

    6. Go to your email and copy the command given
        
        A command line will be sent to you. Copy it and paste into the NickServ 
        window. Some like that will be showed:

        Thank you for verifying your e-mail address! You have taken steps in 
        ensuring that your registrations are not exploited.

    7. Start to use it
        
        In the NickServ window, you can use the help command to get help. Type 
        this:

            /help

        and all the commands, that the IRC server understands, will be showed

        Now go further and get help of a command. Like this:


            /help join
            /help ping
            /help kick

    8. Join to a channel

        Pidgin offers an option to search for opened channels, so you can join 
        and start to talk with someone. 

        Go to the 'Buddy List' window of pidgin and click on 
        'Buddies>Join a Chat... [Ctrl+C]'
        
        Choose your IRC account and click in 'Room List'

        Several channels will be showed. You can then choose one and enter on it

        An easy way to do this is trying to guess a channel. All the channels has 
        the '#' symbol in the begining of it name. So try out something like:

            /join #music
            /join #movies
            /join #Node.js

        in the NickServ window.

[Pidgin]: https://pidgin.im/
[IRC Protocol]: https://tools.ietf.org/html/rfc2812
