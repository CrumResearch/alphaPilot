To enable the debug mode move the `uidebug.c` file one folder up. So to `selfdrive/ui` and rename to ui.c and delete the old one. To evaluate the results, put run ui.c visiond/visiond and selfdrive/debug/dump.py to see the results.

//TODO: Make a shell script for installing the debug mode.


##How to install 
To enable the debug mode move the `uidebug.c` file one folder up. So to `selfdrive/ui` and rename to ui.c and delete the old one. To evaluate the results, put run ui.c visiond/visiond and selfdrive/debug/dump.py to see the results.

```
#ssh into your EON:

tmux a 
#create a new tab 
cd /data/openpilot/selfdrive/ui
./start.py
# create another tab 
cd /data/openpilot/selfdrive/visiond
./visiond 

# Look at your EON and see it working :) 
```
