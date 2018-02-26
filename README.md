# IT324Prelims
1. Right click on the folder where the files for the website are located and choose Properties.
2. Click on Security tab and then click on Edit button.
3. Check the box on Allow column and Read row. Click on Apply button and then OK button. Do
this also on the other files that are needed by the website.
4. Right click on This PC and choose Manage.
5. Click on “Services and Applications”.
6. Click on “Internet Information Services”.
7. Click on “View Sites” at the Actions Panel.
8. Click on “Add Website” at the Action Panel.
9. On Site name, type “IT324PrelimsPointers” and on Host name, type “ www.IT324PrelimsPointers.com ”.
Choose “Classic .NET AppPool” on the Application pool. The type of the binding will be http, the
IP address will be the IPv4 address of the computer used, and the Port will be the concatenation of
“80” plus "80".
10. Go to “C:\Windows\System32\drivers\etc\hosts”. Right click on the hosts file and for this
manual, choose Notepad++ as the editor. On the last line of the file, press enter and then type the
IP address space “ www.IT324PrelimsPointers.com ” and then save. When prompted, always just click on Yes.
11. Click on “Browse www.IT324PrelimsPointers.com on 192.168.254.110:8080 (http)”.
