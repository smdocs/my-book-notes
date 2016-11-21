#Best Practices and Initial Investigation

###1. Linux Tools needed for investigation
  - strace
  - ltrace
  - gdb
  - lsof
  - ping
  - tcpdump
  - htop
  - traceroute/tcptraceroute
  - ping
  - hexdump
  - tcpdump
  - readelf
  
###2. The 4 Phases of Investigation
 
Good investigation practices should balance the need to solve problems quickly,the need to build your skills, and the effective use of subject matter experts.

1. Initial investigation using your own skills.
Basic information that is needed to investigate any problem are
  - The exact time the problem occurred
  - Dynamic operating system information (information that can change frequently over time without any human intervention, such CPU utilization, mem usage etc)
The following quetions needs to be answered in order to find out more about the problem being investigated.
    - <b>What you were doing when the problem occurred.</b> Were you installing oftware? Were you trying to start a Web server?
    - <b>A problem description.</b> This should include a description of what appened and a description of what was supposed to happen. In other words,how do you know there was a problem?
    - <b>Anything that may have triggered the problem.</b> This will be pretty roblem-specific, but it’s worthwhile to think about it when the problem is till fresh in your mind.
    - <b>Any evidence that may be relevant.</b> This includes error logs from an pplication that you were using, the system log (/var/log/messages), an error essage that was printed to the screen, and so on. You will want to protect ny evidence (that is, make sure the relevant files don’t get deleted until you solve the problem).
  
2. Search for answers using the Internet or other resource.
3. Begin deeper investigation.
3. Ask a subject matter expert for help.
