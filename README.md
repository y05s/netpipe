# netpipe
Network robust pipe with socket connections both input and output ends


wget https://github.com/y05s/netpipe/blob/master/netpipe_0.01-20200724_armhf.deb

sudo dpkg -i netpipe_0.01-20200724_armhf.deb


Functionally the command

   "netpipe host_in port_in host_out port_out"

is equivalent to

   "nc host_in port_in | nc host_out port_out"
   with timeout reconnection
