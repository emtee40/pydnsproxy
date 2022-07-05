# pydnsproxy
python dns proxy that support httpdns and tcpdns, specially useful for China networking environment
pydnsproxy avoids operator dns poisoning pollution through tcp request

 How to use windows

     1. Download pydnsproxy and install it in your preferred location.  (Note: Windows Vista/7 users, please use administrator mode to install)

     2. Set the dns server for your broadband connection (or any other connection with your favorite name) to 127.0.0.1

 enjoy it!

# Linux and Mac
There are currently no packages for linux and mac, but the source code of python can be checked out. Except for manual settings, the usage method is similar to windows.

# Description
What is dns cache pollution?
    See this Wikipedia entry 
    https://en.wikipedia.org/wiki/DNS_spoofing
DNSProxy only provides the function of bypassing DNS cache pollution, and cannot solve the problem of connection reset for you, let alone provide you with proxy server bypassing.  For other businesses, please check "GoAgent".
