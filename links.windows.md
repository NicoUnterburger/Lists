# links.winServer.md
URLs of all relevant stuff for Windows Server and Clients


## Client Administration
 - Enable SSH-Server (https://learn.microsoft.com/de-de/windows-server/administration/openssh/openssh_install_firstuse)
 - Nachträglich AHCI (https://mauriceneumann.de/ahci-modus-nachtraeglich-in-windows-10-aktivieren/)
 - Autologin (https://www.tenforums.com/tutorials/3539-sign-user-account-automatically-windows-10-startup.html)
 - Deploy Standard-Apps (https://4sysops.com/archives/default-file-associations-in-windows-10)
 - Powershell CodeSigning (https://blogs.u2u.be/u2u/post/creating-a-self-signed-code-signing-certificate-from-powershell)
 - RunOnce-Key (https://www.borncity.com/blog/2021/08/08/der-windows-runonce-registrierungsschlssel/)
 - Registry to Powershell converter (https://rzander.azurewebsites.net/registry-to-powershell-converter/amp/) 

### Client Troubleshooting
 - Clear MS Teams Cache (https://blog.valeconsulting.co.uk/2018/09/28/clear-the-microsoft-teams-client-cache/)
 - Hal.dll Fehler (https://www.pcwelt.de/tipps/Hal-dll-Fehler-beim-Windows-Start-beheben-1908634.html)
 - Vertrauensstellung (https://itrig.de/index.php?/archives/1840-Loesung-Die-Vertrauensstellung-zwischen-dieser-Arbeitsstation-und-der-primaeren-Domaene-konnte-nicht-hergestellt-werden.html)
 - Anmeldung Benutzerprofildienst fehlgeschlagen (https://itwelt.org/problemloesungen/windows-1563399712/597-die-anmeldung-des-dienstes-benutzerprofildienst-ist-fehlgeschlagen)
 - Autovervollständigung defekt (http://www.office-loesung.de/ftopic550774_0_0_asc.php)
 - Enable Install-Logging (https://docs.microsoft.com/en-US/troubleshoot/windows-client/application-management/enable-windows-installer-logging)
 - Remove Sophos Tamper Protection (https://support.sophos.com/support/s/article/KB-000036125?language=en_US)

## Server Administration
 - BGInfo for all Users at Startup (https://lerndoku.com/bginfo-beim-start-fuer-alle-user-ausfuehren/)
 - Mehrere RDP-Verbindungen (https://www.tech-faq.net/mehrere-rdp-verbindungen-in-server-2016/)
 - EvalToFull Version (https://www.thomas-krenn.com/de/wiki/Windows_Server_Evaluierungsversion_in_Vollversion_umwandeln)
 - WSUS Cleaner (https://github.com/awarre/Optimize-WsusServer)

## Server Troubleshooting
 - WSUS moechte zu viele Updates (https://administrator.de/forum/neuer-wsus-moechte-zu-viele-updates-installieren-6016872278.html)

## Active Directory
### Tools and public scripts
 - Softerra LDAP Browser (https://www.ldapadministrator.com/softerra-ldap-browser.htm)
 - AD Exploitation Cheat Sheet (https://github.com/Integration-IT/Active-Directory-Exploitation-Cheat-Sheet)
 - Rubeus, toolkit for Kerberos-Interactions (https://github.com/GhostPack/Rubeus)
 - GPOmigrate, migrate GPOs cross domains or forests (https://github.com/GoateePFE/GPOMigration)
 - ADMT, Active Directory Migration Tool (https://www.microsoft.com/en-US/download/details.aspx?id=56570)

### Active Directory migration using ADMT
- German ADMT-Walkthrough (https://www.msxfaq.de/exchange/migration/admt.htm)

### Kerberos and Security
 - How Kerberos works (https://en.hackndo.com/kerberos/)
 - Silver- & Golden Tickets (https://en.hackndo.com/kerberos-silver-golden-tickets/)
 - How Golden Ticket Attack works (https://www.netwrix.com/how_golden_ticket_attack_works.html)
 - AD Walkthrough, Golden Ticket Attack (https://resources.infosecinstitute.com/topics/capture-the-flag/active-directory-walkthrough-series-golden-ticket/)

## Print Nightmare
 - https://www.reddit.com/r/sysadmin/comments/ob4s06/printnightmare_0day_exploit_allows_domain_takeover/
 - https://www.borncity.com/blog/2021/07/01/poc-fr-windows-print-spooler-schwachstelle-ffentlich-hohes-rce-risiko/
 - https://blog.truesec.com/2021/06/30/fix-for-printnightmare-cve-2021-1675-exploit-to-keep-your-print-servers-running-while-a-patch-is-not-available/
 - https://www.heise.de/news/PrintNightmare-Schadcode-Luecke-in-Windows-bedroht-ganze-Netzwerke-6124838.html