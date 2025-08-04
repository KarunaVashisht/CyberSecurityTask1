# CyberSecurityTask1
Task 1: Scan Your Local Network for Open Ports

Overview : This project demonstrates basic network scanning and packet capture activities performed in a virtualized Kali Linux environment using Nmap and Wireshark.
<h4>Tools Used</h4>
<ol>
<li>VMware Workstation Pro</li>
<li>Kali Linux (Guest OS)</li>
<li>Nmap (Network Mapper)</li>
<li>Wireshark (Packet Analyzer)</li>
</ol>

<h4>Commands Used:</h4>
<ul>
  <li>Check Nmap Version:<br>nmap --version</li>
  <li>Check IP Address<br>ifconfig</li>
  <li>Perform TCP SYN Scan<br>nmap -sS 192.168.1.0/24</li>
  <li>Store Scan Output in a Text File<br>nmap -sS 192.168.1.0/24 > scan_Result.txt</li>
  <li>Packet Capture in Wireshark<br>
    <ul type='circle'>
      <li>Captured network traffic while running Nmap scan.</li>
      <li>Saved as: wiresharkscan.pcapng</li>
    </ul>
  </li>
</ul>

<h3>References</h3>
<ul>
  <li><a href="https://github.com/KarunaVashisht/CyberSecurityTask1/blob/main/scan_Result.txt" target="_blank">Scan Output: scan_Result.txt</a></li>
  <li><a href="https://github.com/KarunaVashisht/CyberSecurityTask1/blob/main/ScanningReport.pdf" target="_blank">Scan Explanation: ScanningReport.pdf</a></li>
  <li><a href="https://github.com/KarunaVashisht/CyberSecurityTask1/blob/main/wiresharkscan.pcapng" target="_blank">Wireshark Capture: wiresharkscan.pcapng</a></li>
  <li>Command Screenshots:
    <ul>
      <li><a href="https://github.com/KarunaVashisht/CyberSecurityTask1/blob/main/ifconfig.png" target="_blank">ifconfig.png</a></li>
      <li><a href="https://github.com/KarunaVashisht/CyberSecurityTask1/blob/main/nmap.png" target="_blank">nmap.png</a></li>
      <li><a href="https://github.com/KarunaVashisht/CyberSecurityTask1/blob/main/synScan.png" target="_blank">synScan.png</a></li>
    </ul>
  </li>
</ul>

