# breakfold
 #       v.1.0
This small tool will help you to increase your blog view traffic with Differnet IP for each request with different User-agent.

# screenshot 

![ss_breakfold](https://user-images.githubusercontent.com/48474764/60716355-ce545c00-9f3c-11e9-802e-7e7731fc7292.png)

# Requirements 

1) Tor
2) stem library
3) Python3

# Tested on kali Linux, Pop OS

works only on Linux

# ! Installation !

Linux

`apt-get install tor`

Set your Password for Tor

`tor --hash-password "ThePassCode"`. It will give a hashcode for the string "ThePassCode", Copy the Hashcode.

Now open tor configuration file it is usually located in /etc/tor/torrc and uncomment following lines. And edit the `HashedControlPassword 16:` attribute.

`ControlPort 9051`

`HashedControlPassword 16:<Put the previously copied hashcode here>`

Save the file and exit.


`pip install stem`

`pip install pysocks`

`service tor restart`

If you are using both python version on single machine use pip3 for python3

# How to use

`git clone https://github.com/unstabl3/breakfold.git`

`cd breakfold`

`chmod 744 breakfold.py`

`python3 breakfold.py`

`enter the tor password what you set earlier (for example: "ThePassCode")`

`enter blog address with protocol (for example: https://abstractblog.blogspot.com/paper1.html)`

`enter number of views you want (for example: 5)`

`Now blog will be visited with different ip and User-Agent`

# Support

https://twitter.com/chaskar_shubham

This is in beta version and support for this is minimal.

# Disclaimer

Author will not take any responsibility of your activity using this tool.
For Educational purpose only.

# Credits
@vaibhav yadav for suggesting the name

# License

MIT License
