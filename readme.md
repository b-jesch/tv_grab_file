<h1>tv_grab_file - a simple file grabber for XML EPG files</h1>
<h2>Usage</h2>
Simply open a terminal and copy the source code from here to /usr/bin. Set the permissions of the downloaded file to readable and executable: chmod a+rx. Restart TVHeadend.
<p>

Open the TVHeadend Web Interface. Go to config, channel/EPG, EPG grabber modules. Enable the grabber module "internal:XMLTV:Simple file grabber" and set the "extra module parameter" to the absolute path that points your XML file. Don't forget to save the changes.

Enjoy!

    cd /usr/bin
    wget https://raw.githubusercontent.com/b-jesch/tv_grab_file/master/tv_grab_file
    chmod a+rx tv_grab_file

Note: On some systems you need root privileges to do that above!