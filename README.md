
# **Network Mapping Program**

### A network mapping program written in Python.


This is a visualization program that takes a user's packet capture, either a PCAP-like file or CSV file to create a node-based network map so you can see the most frequent connections made to a network. This program can also visualize network threats when using BRIM, an external, third-party program with built in Suricata to analyze network traffic and create alerts to threats.

This program can be run by double clicking main.pyw or by loading main.pyw into Python and running it directly through Python.

The program has several dependencies including:

Python packages -
- Pandas https://pypi.org/project/pandas/ pip install pandas / pip3 install pandas
- Matplotlib https://pypi.org/project/matplotlib/ pip install matplotlib / pip3 install matplotlib
- NetworkX https://pypi.org/project/networkx/ pip install networkx / pip3 install networkx
- PyVis https://pypi.org/project/pyvis/ pip install pyvis / pip3 install pyvis
-	PySimpleGUI https://pypi.org/project/PySimpleGUI/ pip install pysimplegui / pip3 install pysimplegui

External/third-party programs -
-	BRIM https://www.brimdata.io/
		<br>Install using default settings. Needs to be running whilst main.pyw is running. The ZNG and PCAP samples provided in   main/Samples can be imported directly into BRIM. These imports are called Pools.
-	TShark (installed alongside Wireshark) https://www.wireshark.org/
		<br>Install using default settings. Needs to be installed to your device so that PCAP files can be converted to CSV files.
	
#### Menu Preview <br><br><img src="https://user-images.githubusercontent.com/116100231/197451906-5713cb84-9f06-434e-8f9e-1023b13fd191.png" width="280" height="260">

#### Usage Preview <br><br><img src="https://user-images.githubusercontent.com/116100231/198220279-cf01882f-76f6-4f7e-b88f-40c0204c73d1.png" width="280" height="320">

#### Map Preview <br><br><img src="https://user-images.githubusercontent.com/116100231/197452060-754d23e5-b312-4f73-bbcd-28b702913315.png" width="320" height="180">
