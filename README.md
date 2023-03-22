# CTF-WriteUp
##Using NMAP for scanning (NCL GYM)

###Test your understanding of port scanning by scanning ports.cityinthe.cloud and answering these questions.

Q1) What is the lowest open TCP port on the system?

*NMAP option -pN : tells nmap to skip the ping test and simply scan every target host provided.*
*Since I want to check the domain for open TCP ports and their respective numbers I run the code:*
*#nmap -pN ports.cityinthe.cloud*

![Q1](https://user-images.githubusercontent.com/55906428/226954144-e45717a1-b9e7-4863-a01e-356415f279a1.gif)

Q2) What is the second lowest open TCP port on the system?

*#nmap -pN ports.cityinthe.cloud*
![Q1](https://user-images.githubusercontent.com/55906428/226954709-e198fdb7-cf25-4ed2-bdd4-80fb8a4e70da.gif)

Q3) What is the third lowest open TCP port on the system?

*#nmap -pN ports.cityinthe.cloud*

![Q1](https://user-images.githubusercontent.com/55906428/226954796-9629153d-61ff-49a7-b347-6d12b5fa339d.gif)

Q4) What is the lowest open UDP port on the system?

*the -sU option is for UDP scans*
*the -F option Fast Mode: scan fewer ports than the default scan*
*#sudo nmap -sU -F ports.cityinthe.cloud*

![Q4](https://user-images.githubusercontent.com/55906428/226965733-d651f800-7fe8-4f91-8f30-b44e1ce3aca6.gif)

Q5) What software is being run on TCP port 16080?
