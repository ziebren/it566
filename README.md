# it566

Name: Wireshark

Description: Wireshark is a free and open-source packet analyzer. It is used for network troubleshooting, analysis, software and communications protocol development, and education. 

Your personal review: This is a great tool to capture packets as well as analyze them. With the capturing feature, it gets the entirety of the packets entering and leaving the system. You can then export the data to another program to recontruct the data from the packets to a more userful state. As for reading packet captures, you are able to filter packets with very specific keywords to find exactly what you want. You can follow streams to view a TCP handshake and data transfer very easily.

Your personal notes on usage: ip.addr ==, ip.dst ==, can right click on any flag of packet and prepare as filter to find packets with that flag set

Source URL (if applicable): https://www.wireshark.org/download.html
Local Source (if applicable)

Name: DNS Blacklist
Description: This script takes a
text file created by the log source or analyst and compares it to lists of IP addresses and domains that have been blacklisted.
Your personal review: This is good if you know what you are looking for, but don't know the specifics of that thing. For instance, if you have evidence that points to an attacking that might have come from an Arabic country (like finding arabic words in the chat), then you can download a black list of IP addresses that are associated with Arabic countries. 
Your personal notes on usage: A list of black listed IP's are available all over the internet. Make sure that you can trust the source, or compile the list yourself from addresses you've seen on the firewall.
Source URL (if applicable): https://bitbucket.org/ethanr/dns-blacklists/
Local Source (if applicable)

Name: ELK Stack
Description: This bundle, referred to as the ELK Stack, combines three tools together that allows for the analysis of large sets of data. The ELK Stack is comprised of three components. The first of these is Elasticsearch. Elasticsearch is a log searching tool that allows for near real-time searching of log data.
The next component in the ELK Stack is Logstash. Logstash is the mechanism that handles the intake of log files from the sources across the network, process log entries, and finally, allows for their output through a visualization platform.
The final component of the ELK Stack is Kibana. Kibana serves as the visual interface or dashboard of the ELK Stack.
Your personal review: Although it does require a lof of setup, it allows you to perform queries against log files for such elements as user IDs, IP addresses, or log entry numbers. Kibana is a great way to visualize all the data gathered from the logs of different processes and systems. You can create your own graphs to show the data you want to see. And it updates with the data that comes in.
Your personal notes on usage: 
Top series on how to install an ELK stack: https://www.youtube.com/watch?v=f_cAbYyuL-c
Good reference on how to create filters: https://www.elastic.co/guide/en/kibana/current/field-filter.html
Different beats to install: https://www.elastic.co/guide/en/beats/libbeat/current/beats-reference.html
Source URL (if applicable)
Local Source (if applicable)

Name: Volatility
Description: Volatility is an open source advanced memory forensics framework.
Your personal review
Your personal notes on usage
Source URL (if applicable)
Local Source (if applicable)

Name
Description
Your personal review
Your personal notes on usage
Source URL (if applicable)
Local Source (if applicable)
