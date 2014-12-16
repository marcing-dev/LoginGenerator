LoginGenerator
==============

Java app for generating usernames from gathered data. Currently it works (or should work) in interactive mode.
Below some usage example:<br/>
<br/>
<b>java -jar LoginGenerator.jar</b><br/>
<pre>
usage: LoginGenerator.jar<br/>
 -d,--dataline-contain <string>		only lines conatining that string will be used<br/>
 -h,--help                        print this message<br/>
 -i,--interactive                 interactive mode can be used with inputfile<br/>
 -in,--input-file <file>          input file<br/>
 -out,--output-file <file>        output file. Default stdout<br/>
 -q,--quiet-mode                  prints only result and errors when not interactive<br/>
 -r,--remove-char <string>        remove that chars from data lines (space separated)<br/>
 -t,--data-type <string>          determine data type in lines, separated with space. Each line can<br/>
                                  have data like: NAME, SURNAME, NICKNAME, EMAIL.<br/>
                                  f.e. line "James Bond 007@mi6.uk" got "NAME SURNAME EMAIL".<br/>
                                  Default: name surname email<br/>
</pre>                                  
<br/>
<b>java -jar LoginGenerator.jar -i</b><br/>
[+] filename to process:data.txt<br/>
[+] got file:data.txt. Is that right? ([Y]/n)<br/>
[+] want me to print it? (y/[N]) y<br/>
<br/>
Development:<br/>
Samuel Pickwick - pickwick@herot.net<br/>
Nathaniel Winkle - winkle@herot.net<br/>
Augustus Snodgrass - snodgrass@herot.net<br/>
Tracy Tupman - tupman@herot.net<br/>
Sam Weller - weller@herot.net<br/>
Tony Weller - tweller@herot.net<br/>
Estella Havisham - havisham@herot.net<br/>
Abel Magwitch - magwitch@herot.net<br/>
Philip Pirrip - pirrip@herot.net<br/>
<br/>
<br/>
Testing:<br/>
Nicholas Nickleby - nickleby@herot.net<br/>
Ralph Nickleby - rnickleby@herot.net<br/>
Newman Noggs - noggs@herot.net<br/>
Wackford Squeers - squeers@herot.net<br/>
Thomas Pinch - pinch@herot.net<br/>
Mark Tapley - tapley@herot.net<br/>
Sarah Gamp - gamp@herot.net<br/>
<br/>
<br/>
Marketing:<br/>
Jacob Marley - marley@herot.net<br/>
Ebenezer Scrooge - scrooge@herot.net<br/>
Bob Cratchit - cratchit@herot.net<br/>
<br/>
<br/>
Human Resources:<br/>
Bill Sikes - sikes@herot.net<br/>
Jack Dawkins - dawkins@herot.net<br/>
Noah Claypole - claypole@herot.net<br/>
<br/>
[+] does every (non empty) line contain data? ([Y]/n) n<br/>
[+] do data lines have something in common? ([Y]/n)<br/>
[+] and that is: @<br/>
[+] print provided lines? ([Y]/n)<br/>
<br/>
Samuel Pickwick - pickwick@herot.net<br/>
Nathaniel Winkle - winkle@herot.net<br/>
Augustus Snodgrass - snodgrass@herot.net<br/>
Tracy Tupman - tupman@herot.net<br/>
Sam Weller - weller@herot.net<br/>
Tony Weller - tweller@herot.net<br/>
Estella Havisham - havisham@herot.net<br/>
Abel Magwitch - magwitch@herot.net<br/>
Philip Pirrip - pirrip@herot.net<br/>
Nicholas Nickleby - nickleby@herot.net<br/>
Ralph Nickleby - rnickleby@herot.net<br/>
Newman Noggs - noggs@herot.net<br/>
Wackford Squeers - squeers@herot.net<br/>
Thomas Pinch - pinch@herot.net<br/>
Mark Tapley - tapley@herot.net<br/>
Sarah Gamp - gamp@herot.net<br/>
Jacob Marley - marley@herot.net<br/>
Ebenezer Scrooge - scrooge@herot.net<br/>
Bob Cratchit - cratchit@herot.net<br/>
Bill Sikes - sikes@herot.net<br/>
Jack Dawkins - dawkins@herot.net<br/>
Noah Claypole - claypole@herot.net<br/>
<br/>
[+] can we move on to the next steps? ([Y]/n)<br/>
[+] only data (and spaces) must be present in lines<br/>
[+] do you want delete some chars? (y/[N]) y<br/>
[+] print provided lines? ([Y]/n) n<br/>
[+] what can be deleted? -<br/>
[+] what type instead that? (empty input will delete it)<br/>
[+] print provided lines? ([Y]/n)<br/>
<br/>
Samuel Pickwick  pickwick@herot.net<br/>
Nathaniel Winkle  winkle@herot.net<br/>
Augustus Snodgrass  snodgrass@herot.net<br/>
Tracy Tupman  tupman@herot.net<br/>
Sam Weller  weller@herot.net<br/>
Tony Weller  tweller@herot.net<br/>
Estella Havisham  havisham@herot.net<br/>
Abel Magwitch  magwitch@herot.net<br/>
Philip Pirrip  pirrip@herot.net<br/>
Nicholas Nickleby  nickleby@herot.net<br/>
Ralph Nickleby  rnickleby@herot.net<br/>
Newman Noggs  noggs@herot.net<br/>
Wackford Squeers  squeers@herot.net<br/>
Thomas Pinch  pinch@herot.net<br/>
Mark Tapley  tapley@herot.net<br/>
Sarah Gamp  gamp@herot.net<br/>
Jacob Marley  marley@herot.net<br/>
Ebenezer Scrooge  scrooge@herot.net<br/>
Bob Cratchit  cratchit@herot.net<br/>
Bill Sikes  sikes@herot.net<br/>
Jack Dawkins  dawkins@herot.net<br/>
Noah Claypole  claypole@herot.net<br/>
<br/>
[+] do you want delete some chars? (y/[N])<br/>
[+] each line can have data like: NAME, SURNAME, NICKNAME, EMAIL<br/>
[+] f.e. line "James Bond 007@mi6.uk" got "NAME SURNAME EMAIL"<br/>
[+] does every line contain the same type of data? ([Y]/n) Y<br/>
[+] looking on example above, what types of data we have (space between)? name surname email<br/>
[+] parsing data...<br/>
[+] successfully generated 486 unique usernames<br/>
[+] provide filename for output (none for stdout): out.txt<br/>
[+] usernames saved to file: out.txt<br/>
[+] done! Bye!<br/>
<br/>
<br/>
