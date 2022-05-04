# RDPassSpray
Mild edits to the script made by https://github.com/xFreed0m

HEY! So I needed a RDP paswword sprayer for some CTFs and I found this one by https://github.com/xFreed0m
Github link: https://github.com/xFreed0m/RDPassSpray
It's a cool and useful script but there's a couple things I wanted to change like colours
Also, I found that getting the hostnamectl part working to be a little painful. I actually tried removing the functionality but didn't like the end result
My suggestion to get it working is to add the suid bit to hostnamectl
sudo chmod u+s /usr/bin/hostnamectl
