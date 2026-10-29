Project Overview
This is my first hands-on cybersecurity project! I built a safe virtual lab on my computer using VirtualBox and Kali Linux.

By putting the virtual machine (VM) on a private internal network, I created a safe "sandbox"—a completely isolated environment where I can practice using security tools and ethical hacking techniques without any risk to my home network or main computer.

🎯 What I Built & Configured
Virtual Box & Kali Linux: Downloaded, installed, and configured a brand-new Kali Linux virtual machine.

Custom NAT Network: Created a special network inside VirtualBox so my VM can connect to the internet while staying isolated from my main host computer.

Static IP Setup: Manually assigned a fixed IPv4 address, subnet mask, and DNS server directly inside Kali Linux so its address never changes.

Base Snapshots: Took a clean restore point (snapshot) right after setup was finished so I can easily undo any mistakes later.

🛠️ What I'm Using This Lab For
Now that the lab is up and running, I use it to practice basic cybersecurity skills.

💡 What I Learned Along the Way
NAT vs. NAT Network: I used to think all NAT settings were the same! Standard NAT puts a single machine in its own bubble, but a NAT Network lets multiple virtual machines on the same subnet talk to each other while still sharing an internet connection.

Setting Up Static IPs: I learned how to set up manual IPv4 addresses in Linux, which is super important when you need lab machines to find each other consistently.

The Power of Snapshots: Taking a clean snapshot right after setting everything up is a lifesaver. If I mess up a configuration or break the OS during an experiment, I can reset it back to working order in 10 seconds.

Why Notes Matter: Documenting my steps, settings, and troubleshooting attempts saved me so much time. Keeping clear notes is definitely a habit I'll carry into future projects.
# networkwalks-B084-Wk1-PM1-cybersecurity-lab-setup<img width="1366" height="701" alt="SS 1" src="https://github.com/user-attachments/assets/6d6bd859-95d8-4eff-9adc-a94eea69f717" />
<img width="1366" height="604" alt="ss2" src="https://github.com/user-attachments/assets/80bf5577-c18a-47ed-b0e9-bad4bd7ce230" />
<img width="1366" height="662" alt="VirtualBox_kali-linux-2026 2-virtualbox-amd64_29_10_2026_17_05_30" src="https://github.com/user-attachments/assets/e50f507d-dea5-4ab0-a390-bad9aa3996b2" />
<img width="848" height="542" alt="s4" src="https://github.com/user-attachments/assets/60eacebf-039f-4263-a099-40317cbc44ce" />
<img width="1361" height="638" alt="s3" src="https://github.com/user-attachments/assets/8ebfe244-f9eb-4c69-9230-14e080b31449" />
