# security-tips-macos
security tips for Macos users


set firewall on:<br>
<code> System Preference -> Security & Privacy -> turn firewall on </code><br>
<i> you might need to click the lock icon at the bottom because of <b> administrator privilege </b> </i>

turn firewall on:<br>
<code> System Preference -> Security & Privacy -> FileVault  -> Turn of FileVault </code><br>
<i> you might need to click the lock icon at the bottom because of <b> administrator privilege </b> </i>

use Burp Suite Community Edition<br>
with this tool you can look at the meta data from links <a href=""> URL </a> such as <b> spam e-mails / phising emails </b>
you are able to see if any arbitrary Javascript code is getting executed when clicking the links 

example: 
<code> 
<html><head><title>Loading...</title></head><body><script type='text/javascript'>window.location.replace('http://lycaon.me/undertale.html?js=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJhdWQiOiJKb2tlbiIsImV4cCI6MTY2MDUyMzQ3MiwiaWF0IjoxNjYwNTE2MjcyLCJpc3MiOiJKb2tlbiIsImpzIjoxLCJqdGkiOiIyczVsZGc0M3ZndG1qNjUwZW8wdmkzaTkiLCJuYmYiOjE2NjA1MTYyNzIsInRzIjoxNjYwNTE2MjcyNDY0MTQ5fQ.FmW49LfRDnrvR2S30HpAF3KJbJXIDUyQMwlEsCnl72s&sid=cd23c60e-1c20-11ed-9cfc-2245e7957fa4');</script></body></html> 
</code>

this will look like this <a href="#"> http://lycaon.me/undertale.html </a> but when you are going to the website it takes you to some shady
ad website instead of the website you wanted to 

this is something i found on <a href="https://gaming.stackexchange.com/questions/241785/can-i-ever-play-undertale-again-normally"> https://gaming.stackexchange.com/questions/241785/can-i-ever-play-undertale-again-normally </a>

