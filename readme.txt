
These scripts are to use the Global iTach ip2ir device.

Edit the deviceid.txt file with the ip adress of your iTach box.

If your particular set top box (STB) does not have a corrasponding file in the stddefines directory.
Use the ir learner in the iTach box. To get the ir values. Command get_IRL

The  itach_send has has4 parms
 Device ID: This matches the value in the deviceid.txt
 Iterface ID:  This is the interface on the box will be 1, 2, or 3.
 STB ID: This will match the file name in the stbdefiles dir.
 IR command: This is the command passed by mythtv.

Every time the progeam is run. The log is over written.

In the external channle change line you would enter:
/opt/itach/itach_send 1 1 apex_ad_110w    

Make sure there are spaces after the stb id.

If you with to install this program to a directory other than /opt/itach . You will need to edit the itach_send file

I tryed to keep this system as simple as possible.  Perl is definly not my best lang, but it seemed the fastest path.
If you have any ideas. Feel free to contact me a coder_96@yahoo.com .

