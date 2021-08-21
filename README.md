# AUSVPN-on-Linux
A guide on how to install AUSVPN on linux.

The process is actually pretty straightforward. First download the .tgz file from [here](http://ping.stonybrook.edu/pub/PanGPLinux-5.1.1-c17.tgz)

Next, install using the instructions for your distribution. 
If you're running a debaian based distro like Pop OS, Ubuntu, Elementary OS etc. 
`sudo dpkg -i /path/to/file/install.deb`
If you're running RHEL, Fedora, or CentOS run.
`sudo dnf install /path/to/file/install.rpm`

Once you've got it installed, open your terminal and type the following
`globalprotect connect --portal vpn.aus.edu`

That's it, you should be configured and connected.
To disconnect type in `globalprotect disconnect` to reconnect later type `globalprotect connect`.

That's all!
