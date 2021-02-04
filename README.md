# a telegram GSI request bot made in C#

## how to config it

open the Program.cs file and config the following:
```c#
        // replace with your own bot token
        private static readonly TelegramBotClient bot = new TelegramBotClient("YOUR-TELEGRAM-TOKEN-GOES-HERE");
        // replace with the chat you want the bot to work on
        private static long chat = 123; // you can type your own id if you want the bot to message you with the link
        // replace with the chat you want the bot to send the gsi messages to
        private static long chat_send = 321;
```
<br>

## how to run it?

you must have the .NET sdk installed on your machine <br>

now run the following: <br>

`git clone https://github.com/Velosh/CS-Request-bot bot` <br>
`cd bot` <br>
now config the bot as said above <br>

then run: <br>
`dotnet run -c Release` <br>

## how to use the commands?

`/request <link> <optinal: info>` <br>

e.g: <br>

`/request https://pilotfiber.dl.sourceforge.net/project/havoc-os//tulip/Havoc-OS-v3.12-20210103-tulip-Official.zip don't resign this rom!`