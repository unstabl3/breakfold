# breakfold
 #       v.1.0
This small tool will help you to increase your blog view traffic with Differnet IP for each request with different User-agent.

# screenshot 

![ss_breakfold](https://user-images.githubusercontent.com/48474764/60716355-ce545c00-9f3c-11e9-802e-7e7731fc7292.png)

# Requirements 

1) Tor
2) stem library
3) Python3

# Tested on kali Linux

# ! Installation !

Linux

`apt-get install tor`

Now open tor configuration file it is usually located in /etc/tor/torrc and uncomment following lines.

`ControlPort 9051`

`HashedControlPassword "your password"`

Save the file and exit.

`service tor restart`

`pip install stem`

If you are using both python version on single machine use pip3 for python3

# How to use

`git clone https://github.com/unstabl3/breakfold.git`

`cd breakfold`

`chmod 744 breakfold.py`

`python3 breakfold.py`

`enter your tor password from torrc file`

`enter blog address with protocol`

`enter number of views you want`

`Now blog will be visited with different ip and User-Agent`

# Support

https://twitter.com/chaskar_shubham

# Disclaimer

Author will not take any responsibility of your activity using this tool.
For Educational purpose only.

# License

MIT License
