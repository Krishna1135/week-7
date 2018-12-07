# week-7

Time Spent:  9 hours spent in total

> Objective: Find, analyze, recreate, and document **five vulnerabilities** affecting an old version of WordPress

## Pentesting Report
1. (Required) Vulnerability Name or ID
  - [ ] Summary: 
    - Vulnerability types: XSS
    - Tested in version: 4.2
    - Fixed in version:4.2.15 
     
  - [ ] GIF Walkthrough:  <a href="https://imgur.com/bbqmO2N"><img src="https://i.imgur.com/bbqmO2N.gif" title="source: imgur.com" /></a>
  - [ ] Steps to recreate: 
  i)  Go the the dashboard and open a comment section 
  ii) I wrote a comment on a page that has 64kb of content.  
  iii) I wrote 64,000 As in a comment box and posted it. 
 
  - [ ] Affected source code: I dont think there was an effected source code but this says about a vulnerability.
  
  
 2. (Required) Vulnerability Name or ID
  - [ ] Summary: 
    - Vulnerability types: User Enumeration Exploit
    - Tested in version: 4.2
    - Fixed in version:4.7
     
  - [ ] GIF Walkthrough:  
  <a href="https://imgur.com/w8GCqm9"><img src="https://i.imgur.com/w8GCqm9.gif" title="source: imgur.com" /></a>

  - [ ] Steps to recreate:
  i) I tried to login the wp distillery using different usernames like Kirshna and admin1. 
  ii)  Then I tried admin as the username. It worked because it was the correct one.
 
 
 
 3. (Required) Vulnerability Name or ID
  - [ ] Summary: 
    - Vulnerability types: XSS
    - Tested in version: 4.2
    - Fixed in version:4.1.5
     
  - [ ] GIF Walkthrough:   <a href="https://imgur.com/RRTkK6V"><img src="https://i.imgur.com/RRTkK6V.gif" title="source: imgur.com" /></a>
  
  - [ ] Steps to recreate: 
  i)  In the main page, I went to the comment section.
  ii)  Under leave a reply part I posted a comment
  iii) The comment is: <script>while(1)/{alert(document.cookie);}<script>
  iv) Once this is commented it shows that this is a vulnerability on the top of the screen.
  
  - [ ] Affected source code: there is not an affected cource code however this says about a vulnerability.
  
  
  4. (Required) Vulnerability Name or ID
  - [ ] Summary: 
    - Vulnerability types: XSS
    - Tested in version: 4.2
    - Fixed in version:4.1.15  
  - [ ] GIF Walkthrough:  <a href="https://imgur.com/Fiwtvn5"><img src="https://i.imgur.com/Fiwtvn5.gif" title="source: imgur.com" /></a>
  - [ ] Steps to recreate:
  
  i) Go to the WP Distillery main page 
  
  ii) Post a comment:
  <script>“alert (XSS in a comment”)</script>
  
  iii) Once the above script is posted in the comment section, you can see the small notification in the top part of the screen saying that XSS vulnerability found in the comment.
  
  
  
    
  5. (Required) Vulnerability Name or ID
  - [ ] Summary: 
    - Vulnerability types: XSS
    - Tested in version: 4.2
    - Fixed in version:4.1.5  
  - [ ] GIF Walkthrough: <a href="https://imgur.com/3q2eYPm"><img src="https://i.imgur.com/3q2eYPm.gif" title="source: imgur.com" /></a>
    
    
     - [ ] Steps to recreate:
  
  i) Go to the main page of the WP Distillery.
  
  ii) find the post section and post the following script
  
  <script>alert ("XSS in a comment”)</script>
  
  iii) Once the above script is posted , you can see the small notification in the top part of the screen saying that XSS vulnerability.
    
    
    
   
