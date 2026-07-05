Room: Intro to Offensive Security
Link: https://tryhackme.com/room/offensivesecurityintro
Status: Completed

Summary
Worked through a beginner offensive security scenario involving a 
simulated bank website. The objective was to locate a hidden admin 
page that was not linked anywhere on the visible site, then access 
it to demonstrate the impact of leaving such pages undiscoverable 
but unsecured.

Tool used
Gobuster - directory and file brute-forcing tool. Takes a wordlist 
and checks each entry against the target URL to identify pages that 
respond with status code 200.

Concepts learned
- Difference between offensive (red team) and defensive (blue team) 
  security roles
- Security through obscurity is not a valid security control - 
  hiding a page without authentication or access control still 
  leaves it exploitable
- Basics of directory brute-forcing
