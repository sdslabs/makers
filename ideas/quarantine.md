# Ideas list for the Quarantine Edition

* __Mouse over Wifi__: Connect a wireless mouse (the one with dongle, not bluetooth one) to raspberry pi, make a wifi hotspot from it. connect your laptop to the wifi. Challenge is to make the mouse connected to raspi work for your laptop, it should move the pointer in laptop, not RPi. Sort of KVM Switch, but need to be very lightweight. KVM reference(https://www.leostream.com/leostream-blog/implementing-a-kvm-switch-what-is-it-why-would-i-want-one-where-are-the-gaps/)

* __Brave extension__: A single firefox extension that adds all the main functionality of brave browser(no ads, https everywhere, tracker blocker, etc) to firefox. It will be more better if something can be just like that but firefox based. Developing a firefox extension (https://blog.mozilla.org/addons/2014/06/05/how-to-develop-firefox-extension/)

* __Github activity tracker__: Build a tool that checks all activity(pull requests, reviews, commits, merges) of a user in all the repositories in a github organisation. You can use github API for this purpose (https://developer.github.com/v3/).

* __CoViD__: Build a COVID-19 cases web visulaizer similar to Worldometer - https://www.worldometers.info/coronavirus/ You can let your imagination run wild and build visuals including different types of graphs, scatter plots , tables etc. You may checkout https://rapidapi.com/KishCom/api/covid-19-coronavirus-statistics and https://covid-19-apis.postman.com/ for reference. 

* __Adaptive screen brightness__: Build a tool that monitors the average pixel values of the screen, and reduces the brightness when moving from a dark to a light screen to reduce eye strain. 

* __Covid simulator__: Build a Monte Carlo simulator for COVID-19 that allows the user to change parameters like population, density, travel frequency etc. You can use datasets on Covid 19 from Kaggle.  Bonus points if you use webassembly. For reference check out https://blogs.mathworks.com/simulink/2020/03/23/covid-19-simulating-exponential-spread-in-simulink/

* __hot-reloader__: Build a tool that runs a specific set of commands when you update your code (hot-reloading). You can add specific predefined tasks depending on languages and frameworks too :) Checkout https://github.com/vrongmeal/leaf for some inspiration.

* __Play Desktop__: Electron application for a distributed play queue(something on distributed queues to learn about https://www.freecodecamp.org/news/a-dummys-guide-to-distributed-queues-2cd358d83780/) with support for local songs play and integration with youtube.

* __feed-cli__: Build a cli tool that provides daily feeds and trending headlines in your terminal. Use web scrapping to scrape the data from news websites. Add some flags for category of the news,  news agency or the area for which news is needed. A reference is https://newsbeuter.org/

* __Controller to Keyboard converter__: Write a tool that detects a game controller and translates its button presses to keyboard key presses. You can optionally allow the user to rebind controller buttons to different keyboard keys. You might want to look at https://docs.microsoft.com/en-us/windows/win32/xinput/getting-started-with-xinput to get started with xinput.

* __Automatic wireless switcher__: A tool which checks the connected wifi speed and compares it with other nearby wifis which can be automatically connected to and makes an auto switch without user interface. The tool should continously other available network as if it were virtually connected to it and if a particular network becomes more viable than the present network then it should make the switch.

* __Github Life Saver!__: Build a tool that helps one use github in visual manner, on the same lines as the blueprinting system is implemented in Unreal Engine 4. Each commit is a rectangle on a plane, whereas each branch is a plane parallel to the x-y plane. One can switch between branches as well as commits on any branch by simply dragging and dropping the head of the arrow onto that commit/branch. Each commit block must have all the necessary visualisation clearly showing the changes made. Very important: Make a Undo/Redo button that will change the repo back in the state it was before the user messed with it.

* __CLI for Torrent Search and download__: A CLI tool that will use the PirateBay API https://rapidapi.com/volodimir.kudriachenko/api/ThePirateBay/details and choose the best torrent based on seeders and leechers. Use transmission CLI to download the file. The whose process should be as simple as &lt;cli-tool&gt; download &lt;search-item&gt;

* __Algorithm Visualizer__: A web based interface to visuallize various CP algorithms with benchmarking. D3.js can be used for the visualization. You can start with simple algorithms like sorting algorithms or search algorithms like the DFS and BFS.
