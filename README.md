# Golden-Ticket
The Kerberos Golden Ticket is an attack in which threat agents can create/generate tickets for any user in the Domain, therefore effectively acting as a Domain Controller



To get the Golden Ticket I initially ran a shell as "bob" again because I still have his password. 

<img width="936" height="279" alt="image" src="https://github.com/user-attachments/assets/dcd1960c-ecab-4cfb-90e7-25359b082df2" />


Once I was in as bob I then ran Mimikatz with the commands found in the HTB document

<img width="816" height="416" alt="image" src="https://github.com/user-attachments/assets/a49aa6fc-4fe1-48f7-8cfa-31b14fd9e8a3" />


After running Mimikatz I was able to find the NTLM Hash 

<img width="708" height="317" alt="image" src="https://github.com/user-attachments/assets/f0efff9f-46d5-40fe-bebf-16d7121af92d" />
