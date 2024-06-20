# q_firewalld_config

This is a bash script that configured firewalld on Linux for running Qumulo software on generic Linux.
Firewalld is not required to run Qumulo on Linux so stopping/disabling it will work, however for those who want to use it, this script will open up the proper ports to allow Qumuluo to function.

Note:  Not every customer will necesarily need every port, but this should allow all services to work.  Edit the port list to taste but be sure to test your config if you do so.

For a list of what each port is doing, see https://docs.qumulo.com/azure-administrator-guide/network-configuration/required-ports.html

Special thanks to Tony Raliegh for help on this project.
