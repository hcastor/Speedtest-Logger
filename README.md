# Speedtest-Logger
This script logs speedtest results to a text file. It is to be setup as a cron job, and run every x minutes. I set mine up with windows event manager, and ran it every 20 minutes. 

# Why?
I lived in an apartment complex where the Internet was unusable from the hours of 4pm - 2am, every day like clockwork. Being a computer science major, and basically everything else I do requiring an Internet connection, this was not acceptable. The apartment management claimed it wasn't a problem on their end, and it was something to do with my router. I knew this not to be the case, so I created this script to take a speed test every 20 minutes, to show them that the ping would be absurdly high for over 8 hours a day. The most important 8 hours a day for a college student, mind you. This effectively meant I didn’t have Internet for months. You can see the results I gave them in the results.pdf. The first graph is the ping over a single day, highlighting the bad hours. The second graph is a graph of all the speed tests I had ever taken since move in date. You may have to download the file and zoom in to get a clearer image. Github's pdf viewer doesn't do a good job.

# Requirments
speedtest-cli https://pypi.python.org/pypi/speedtest-cli/