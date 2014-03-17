Sugar-build: an alternative to Sugar-JHbuild for Fedora 17
================

We have seen a complex process involved in building sugar on fedora 14 using JHBuild. Now we have an easy way out to build and run sugar by using sugar-build.

sugar-build it is an alternative of sugar-jhbuild developed by Daniel Narvaez that allow us to get a development version of Sugar easier than with sugar-jhbuild. Also, it works on Fedora 16, 17 and Ubuntu 12.

These are the steps to build and run sugar on the fly using sugar-build:
Get the source code
---------------
You need to get the latest repository of sugar using git

    $ git clone git://git.sugarlabs.org/sugar-build/sugar-build.git
    
Make
--------------
Then run the make command to build it( It usually takes 20-30 mins depending on processor and RAM)

    $ make
    
you will see such message once make is complete: 
<img src="http://3.bp.blogspot.com/-O5i8KKwbB3w/UAu1omtajQI/AAAAAAAADy4/l4tZ58dBzGQ/s1600/make_complete.png"/>

Run
--------------
Once the make process is complete you should be able to run your sugar environment

    $ make run
    
and here you go....your sugar desktop environment is up and running!
You can switch between your fedora environment and sugar by Ctrl+Alt+F1 and Ctrl+Alt+F3

<img src="http://1.bp.blogspot.com/-EzYF9FHqP3Y/UAu6P26vsjI/AAAAAAAADzM/UKarBgKQqks/s640/Screenshot+of+_Journal_.png"/>

<img src="http://1.bp.blogspot.com/-L3HrC_g-Mr4/UAu6OtqK75I/AAAAAAAADzE/huI3MW65FwI/s640/Screenshot+of+_Home__2.png"/>
