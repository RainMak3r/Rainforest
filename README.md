================================================================================================

F0xChas3r is a forensic tool for extracting and viewing internet artifacts from Mozlila Firefox. The internet artifacts 
include bookmark, auto-complete, download, cookie, DomStorage, history, extension and cache records. All the outputs will
be saved into CSV file with UTC time.

Developer : Andy Yang
Version : 0.1.0
License : GPLv3

================================================================================================

RainMak3r@Could:~/Desktop# ./F0xChas3r.rb 


 ✄╭━━━┳━━━╮╱╱╭━━━┳╮╱╱╱╱╱╱╱╭━━━╮
 
 ✄┃╭━━┫╭━╮┃╱╱┃╭━╮┃┃╱╱╱╱╱╱╱┃╭━╮┃
 ✄┃╰━━┫┃┃┃┣╮╭┫┃╱╰┫╰━┳━━┳━━╋╯╭╯┣━╮
 ✄┃╭━━┫┃┃┃┣╋╋┫┃╱╭┫╭╮┃╭╮┃━━╋╮╰╮┃╭╯
 ✄┃┃╱╱┃╰━╯┣╋╋┫╰━╯┃┃┃┃╭╮┣━━┃╰━╯┃┃  version 0.1.0
  
F0xChas3r - Firefox forensic tool by Andy Yang[contactayangATgmailDOTcom]; 

EXAMPLE USAGE:
     ./F0xChas3r.rb  -p '/Mozilla/Firefox/Profiles/<random text>.default' -c '/Mozilla/Firefox/profiles/<random text>.default/Cache'
  
    -c, --cache path                 specify user cache location.
    -p, --profile path               specify user profile location.
    -h, --help                       display help


================================================================================================
Example of usage.
================================================================================================
RainMak3r@Could:~/Desktop# ./F0xChas3r.rb -p '/RainMak3r/.mozilla/firefox/nq474mcm.default' -c '/RainMak3r/.mozilla/firefox/nq474mcm.default/Cache'

[Info]  F0xChas3r is chasing the Firefox for you now.

[OK]	  11 bookmark records have been found.

[OK]	  4 download records have been found.

[OK]	  21 cookie records have been found.

[OK]  	1 DOM storage records have been found.

[OK]	  2 auto-complete records have been found.

[Info]	Extracting web history could take a few mins.......

[OK]	  97 web browsing history records have been identified.

[Info]	Writing web history records to CSV file.......

[OK]	  3 extension records have been found.

[Info]  F0xChas3r is chasing the Firefox cache records for you now.

[Info]  Extracting cache records could take a few mins.......

[OK]	  112 cache records are identified.

[DONE]	Please check the output CSV files for details.


