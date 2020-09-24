# Yoom! (_Your Own Online Messenger!_)

Open-source. Internet Messenger. Social Media Platform.
Yoom is an open-source Scratch 3.0-powered social media and internet messenger platform. Powered by [CloudLink](https://github.com/MikeDev101/cloudlink).

# Origins
Yoom started off as a Scratch 3.0 project, powered by my SCLE (Super Cloud List Engine). As soon as the public beta was ready for testing, Scratch had a change of rules and projects such as Yoom (cloud messaging projects) were banned.

Shortly after, I abandoned the project. But not for long!
After coming back to Scratch, I stumbled upon the Yoom project in my trash folder, and I thought I would give it a shot.
Sheeptester's HTMLifier had gotten signifigantly better than the last time I used it, and it now had support for custom cloud variable servers! With my existing code, and now access to custom cloud var servers, the Yoom project was reborn, outside of scratch and into your web browser!

# Details
Yoom runs upon SCLE, which uses CloudLink API's TCP WebSocketSecure (WSS) protocols to communicate. A home-grown python websocket server serves as the backbone. 

Downloading the source code file "yoom.sb3" and viewing it VIA [Sheeptester's Modded Scratch 3.0 Editor.](https://sheeptester.github.io/scratch-gui/?width=640&height=360) allows you to view the source code and how everything works. Or, you can view the index.html file for a demo.

# Features

Yoom has a translator (powered by Google Translate), word filter, ~~DM system, Global Chat, and a mailbox (kinda like e-mail)~~ _these features are a work-in-progress, though._

Yoom also has a remote-access feature (only available for moderators), user account creation, temp. and perm. bans.s

# Run Yoom

To run Yoom, you'll need to host a local webserver. Install the CloudLink API server.py file, and run it. See [the CloudLink repo](https://github.com/MikeDev101/cloudlink) for details.
