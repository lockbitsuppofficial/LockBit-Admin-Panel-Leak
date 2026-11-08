# LockBit-Admin-Panel-Leak
Private messages, Bitcoin addresses, victim data, and attacker information were leaked after someone hacked a LockBit admin panel.

Lockbit qTox Contact: 6598FF085E621212EF75082605A8D3BDAD91D99D8E589EC05A369439CF69712F85AF79AE0F7A

On May 7, 2025, the LockBit admin panel was hacked by an anonymous actor who replaced their TOR website with the text ‘Don’t do crime CRIME IS BAD xoxo from Prague’ and shared a SQL dump of their admin panel database in an archived file ‘paneldb_dump.zip’:

There is not much information available regarding the individual identified as 'xoxo from Prague' whose objective seems to be the apprehension of malicious ransomware threat actors. It is uncommon for a major ransomware organization's website to be defaced; more so for its administrative panel to be compromised. This leaked SQL database dump is significant as it offers insight into the operational methods of LockBit affiliates and the negotiation tactics they employ to secure ransom payments from their victims.

Trellix Advanced Research Center’s investigations into the leaked SQL database confirmed with high confidence that the database originates from LockBit's affiliates admin panel. This panel allows the generation of ransomware builds for victims, utilizing LockBit Black 4.0 and LockBit Green 4.0, compatible with Linux, Windows and ESXi systems, and provides access to victim negotiation chats. 

The leaked SQL database dump encompasses data from December 18, 2024 to April 29, 2025, including details pertaining to LockBit adverts (aka ransomware affiliates), victim organizations, chat logs, cryptocurrency wallets and ransomware build configurations. 

The absence of table constraints in the SQL dump initially raised concerns regarding the authenticity and integrity of the provided data, however, further analysis of the leak data demonstrated substantial intelligence and insights on LockBit’s adverts, victim organizations, negotiation tactics and earnings. The details of these findings are addressed in this blog.

