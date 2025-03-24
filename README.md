# ICMP-Test-Tool-v1.0

 
Fields and their required inputs:
1.	Enter source IP Address: The user has to enter the IP address of the machine on which this software is running.
2.	Enter Destination Address: The user has to enter the IP address of the Device Under Test.
3.	Enter Gateway: The user has to enter the gateway IP address of the machine on which this software is running. If the DUT is directly connected, enter the IP address of DUT.
4.	Select Interface: Select the correct network adapter.
5.	Redirect new IP/new Gateway: Enter the new gateway for crafting redirect packet.
6.	Orignal Dst Ip: Enter the IP address which causes redirection.
7.	Press Enter DUT Details button:
In this fill the details as applicable and click Submit.
8.	Optional- If Secure Shell access is available in the DUT, enter the SSH credentials in respective fields.
Also, you can enter multiple ssh commands in csv format.
For example in a sample DUT
ip route show,sudo,<sudopassword>,ls -l
One can escalate privilege by forming a valid comma separated command and entering in the SSH cmd field.
9.	Select the Run default Test case Check box to run test case as per ITSAR. If you want to test a particular ICMP sequence of ITSAR, you can enter manually.
10.	Now click Send ICMP Packets.
11.	If DUT connectivity is established, Red circular indicator will become green and tests will start. At end of the test, a PDF report and HTML report will be generated which will be in the program’s directory.
