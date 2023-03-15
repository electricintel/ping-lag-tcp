# ping-lag-tcp
Fix it

For Windows

Regedit

Backup Registry
File
Export 
name it

Computer\HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows NT\CurrentVersion\Multimedia\SystemProfile
hkey_local_machine
Software
Microsoft
Windows NT
Current Version
Multimedia
SystemProfile
Network ThrottlingINdex
FFFFFFFF
Hexadecimal


Computer\HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\MSMQ
HKEY_LOCAL_MACHINE
Software
Microsoft
MSMQ
(if MSMQ does not exist:
On left menu
Left click on Microsoft Folder
New Key (New Folder #...)
Right Click (New Folder #...) Rename MSMQ)
Righ Menu
Left click New
DWord32 bit
TCPNoDelay
Value to 1

Computer\HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\MSMQ\Parameters
(if Parameters does not exist:
Left Click MSMQ
New Key (New Folder #...)
Right Click (New Folder #...) Rename Parameters)
New on right menu
Dword 32
TCPNoDelay
Modify
Value 1


Computer\HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Services\Tcpip\Parameters\Interfaces\
HKEY_LOCAL_MACHINE
SYSTEM
CurrentControlSet
Services
Tcpip
Parameters
Interfaces
(Look For key with most information on right menu)
New 
Dword 32bit
TCPackFrequency
Set Value to 1
New 
Dword 32bit
TCPNoDelay
Set value to 1




Original
https://www.youtube.com/watch?v=SITimqy5Lxc
0:00
[Music]
0:10
hello everyone how are you doing
0:12
this is mdtech here another quick
0:15
tutorial in today's video I'm gonna show
0:17
you guys how to lower your ping for your
0:20
Windows 10 computer so if any of us play
0:22
online games or use a lot of bandwidth
0:25
from the internet you might notice that
0:26
a high pain correlates to slower
0:28
performance it's done this brief
0:30
tutorial I machine you guys how to
0:32
hopefully speed up your computer's
0:33
internet a little bit so we're gonna
0:36
jump right into it and we're going to
0:37
start by opening up the start button and
0:39
you want to type in regedit RT g e di t
0:44
bestman should say regedit you want to
0:47
right click on it and then left click on
0:49
run as administrator if you receive a
0:52
user account control window you want to
0:53
select yes now into the registry editor
0:57
we want to do now is i'm ashleigh gonna
1:00
make a little bit bigger here so you can
1:01
see where we're going and we're going to
1:03
start by going over and opening up the H
1:05
key local machine folder right here so
1:10
you want to left one little arrow next
1:11
to the H key local machine to expand it
1:13
or you can double click on the folder
1:15
itself to achieve the same result so
1:17
again just expand that now that we've
1:20
done that you want to look for the
1:21
software folder right here expand that
1:24
one as well and now we can go and select
1:27
the Microsoft folder expand that one in
1:30
order to make this side comm a little
1:32
bit wider if you're having trouble
1:33
reading in here just left plugins
1:35
between this bar and you can see a
1:37
little arrow comes up just drag it over
1:39
the right so you can see a little bit
1:40
better as far over as you need to go and
1:43
now you want to go down to the Windows
1:46
NT folder
1:50
right here and you want to expand that
1:52
one as well and now expand the current
1:56
version folder and now go down to
1:59
multimedia right here expand that one
2:02
and now you're going to left click on
2:04
the system profile folder one time until
2:07
you have the screen on the right that
2:09
looks like what it does right here and
2:11
what you want to do now is you want to
2:12
double click on the network throttling
2:14
index entry in here again double click
2:17
on it and now for value data it's very
2:21
important you con me in exactly what I'm
2:23
gonna have on the screen right here and
2:24
you want to type in F and it's very
2:27
important you type in exactly what I
2:29
have on the screen right now and you
2:30
want to type in 8 FS in a row so
2:33
uppercase F so type F F F F F F F F
2:38
until you have eight of them on your
2:40
screen so again there should not be any
2:42
spaces in between all these apps and you
2:45
want to make sure that it appears how it
2:47
does on my screen make sure the base
2:49
over here is set to hexadecimal and then
2:52
once you've ensured that you want to
2:54
click on OK now that you've done that
2:56
we're gonna back out of our folders on
2:58
the left side here so I'm just going to
2:59
collapse them and I'm gonna just go back
3:02
up here and now you want to go
3:05
underneath H key local machine again
3:07
this time go down into system now expand
3:13
the current controller set and you
3:16
should be able to see that I am just
3:17
closing a little arrow on the side but
3:18
you can double click on the folders well
3:20
you want to go down to get to tcp/ip
3:25
you
3:32
right here you expand that one
3:35
and now this should be a parameters
3:37
folder expand that and now there's an
3:41
interfaces folder right here expand this
3:44
one as well by clicking the arrow next
3:45
to it and now you might have a few
3:47
subfolders in here you want to select
3:49
the one that has the diminishment
3:50
information so if you click on all three
3:52
if you have three you want to find the
3:54
one that looks like there's the most
3:55
amount of stuff in here you want to
3:57
right-click inside of some empty space
3:59
near the bottom preferably right click
4:01
like I said and then left click on new
4:05
and then it's like d-word 32-bit value
4:09
and then you want to type in tcp ack and
4:14
the tcp should be all be capital and
4:16
then ack and then type in frequency
4:24
exactly how it appears my screen make
4:25
sure the spelling is correct
4:27
can't stress that enough then you want
4:30
hit enter and now go back down here
4:32
again left click on new swathi word a
4:35
32-bit value again from this list and
4:37
now you want to type in TCP No
4:42
then should be capital and then delay
4:44
the D and delay should be capital and
4:46
then you want hit enter an - also note
4:49
the F and frequency for the previously
4:51
word value we created should be count
4:52
bros well and I should also know it at
4:55
this point that I am going to show you
4:56
guys how to make a backup of your
4:57
registry before you perform any of the
5:00
steps in this video but we're not done
5:01
yet
5:01
I just want to keep you guys informed
5:03
that we are gonna go through how to make
5:05
a backup of your registry yeah we
5:07
recommend you do that before doing
5:09
anything I'm showing in this video but
5:11
we'll do that in a couple minutes here
5:12
once I get further along in the video
5:13
and once we're done with what I'm going
5:15
to show you so now that we've created
5:17
these two values you want to first go to
5:20
the TC pack frequency if we created an
5:22
interest double click on it so now for
5:24
value data in here you want to set it to
5:27
1 and then you want to click on OK and
5:30
you want to go back to the TCP node
5:33
delay
5:34
double click on that so the value data -
5:36
one as well just type the 1 into this
5:38
field here click on OK once you've done
5:40
that and we can back out of some of this
5:42
and you can also note on the top here we
5:44
have the path of where I am so if you
5:46
ever get lost in the video you're more
5:47
than welcome to just refer to this up
5:49
here and once we've done that or we're
5:52
going to do now is navigate over to H
5:55
key local machine again so let's go back
5:58
up to the top close out of this stuff H
6:01
key local machine go down to software
6:04
expand the software folder and now that
6:07
we've expand the software you want to go
6:08
down to Microsoft and then look for a
6:11
folder it says MS MQ
6:15
and you can see in my case I do not have
6:18
one here so if you do not have the MS MQ
6:21
folder you want to go up to the
6:22
Microsoft folder right here right click
6:25
on it left click on new left click on
6:28
the key option now you want to right
6:31
click on which hopefully say new key
6:33
number one and we want to rename it ms
6:35
and the queue if that guide appears on
6:39
my screen so M smq hit enter now that
6:42
we've created this folder in the event
6:44
that it was not already here you want to
6:46
right-click in this space here left
6:48
click on new left click on D worth
6:51
32-bit value now you want to type in
6:53
what we did before tcp all uppercase no
6:56
the end node should be uppercase and
6:58
then delay and then you want to double
7:02
click on it set the value data to 1
7:06
click on ok here and now we want to
7:10
expand the MS MQ folder and we want to
7:12
locate the parameters folder now again
7:15
if you guys do not have a parameters
7:16
folder here we're going to right-click
7:18
on MS MQ left click on new and then
7:21
select key and now you want to type in
7:24
parameters
7:27
pa are amet ers then you want hit enter
7:31
and now on the right side here you want
7:33
to right-click on empty space left quick
7:36
now left click on D word 32-bit value
7:39
from that context menu and following the
7:41
same nomenclature I'm showing in this
7:43
video you want to type in TCP no delay
7:47
again and no should be capital the D and
7:50
delay should be capital as well and you
7:52
want to click the close out of there
7:54
right click on the value left we're
7:57
gonna modify order to double click like
7:59
I was doing previously in the video and
8:02
you want to set that value data to 1 as
8:04
well so again just type the number 1 in
8:07
here and then you want to click on OK
8:11
and that's pretty much it for this
8:13
tutorial guys I do want to show you how
8:15
to create a backup of your registry
8:16
before you pursue of any of those steps
8:18
in this tutorial I don't you would do
8:20
would just be the left foot on the file
8:22
tab up at the top left click on export
8:24
and then you select an export location
8:27
let's say a desktop and I can name this
8:29
whatever I want let me just call it back
8:31
up here click on save and you can see I
8:37
just had the H key local machine folder
8:39
selected but if you just quit on
8:41
computer it would back up your entire
8:42
registry so I did computer up here left
8:46
book file export because you see if it
8:48
had a selected branch was selected
8:50
previously but if we select all then we
8:53
can change the file name again to
8:55
whatever we want backup registry I just
8:59
hit enter to save and then if you ever
9:01
wanted to import the registry to restore
9:03
back your just go up to file import and
9:06
then you would just locate the registry
9:08
entry click on open and that's pretty
9:11
much it guys it's pretty straightforward
9:12
so I do have this brief video was able
9:14
to help you guys out and as always thank
9:17
you for watching and I look forward to
9:18
catching you all in the next tutorial
9:21
goodbye
