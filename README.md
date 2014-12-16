LoginGenerator
==============

Java app for generating usernames from gathered data. Currently it works (or should work) in interactive mode.
Belowe some usage example:

>java -jar LoginGenerator.jar
usage: LoginGenerator.jar
 -d,--dataline-contain <string>   only lines conatining that string will be used

 -h,--help                        print this message
 -i,--interactive                 interactive mode can be used with inputfile
 -in,--input-file <file>          input file
 -out,--output-file <file>        output file. Default stdout
 -q,--quiet-mode                  prints only result and errors when not interactive
 -r,--remove-char <string>        remove that chars from data lines (space separated)
 -t,--data-type <string>          determine data type in lines, separated with space. Each line can
                                  have data like: NAME, SURNAME, NICKNAME, EMAIL.
                                  f.e. line "James Bond 007@mi6.uk" got "NAME SURNAME EMAIL".
                                  Default: name surname email

>java -jar LoginGenerator.jar -i
[+] filename to process:data.txt
[+] got file:data.txt. Is that right? ([Y]/n)
[+] want me to print it? (y/[N]) y

Development:
Samuel Pickwick - pickwick@herot.net
Nathaniel Winkle - winkle@herot.net
Augustus Snodgrass - snodgrass@herot.net
Tracy Tupman - tupman@herot.net
Sam Weller - weller@herot.net
Tony Weller - tweller@herot.net
Estella Havisham - havisham@herot.net
Abel Magwitch - magwitch@herot.net
Philip Pirrip - pirrip@herot.net


Testing:
Nicholas Nickleby - nickleby@herot.net
Ralph Nickleby - rnickleby@herot.net
Newman Noggs - noggs@herot.net
Wackford Squeers - squeers@herot.net
Thomas Pinch - pinch@herot.net
Mark Tapley - tapley@herot.net
Sarah Gamp - gamp@herot.net


Marketing:
Jacob Marley - marley@herot.net
Ebenezer Scrooge - scrooge@herot.net
Bob Cratchit - cratchit@herot.net


Human Resources:
Bill Sikes - sikes@herot.net
Jack Dawkins - dawkins@herot.net
Noah Claypole - claypole@herot.net

[+] does every (non empty) line contain data? ([Y]/n) n
[+] do data lines have something in common? ([Y]/n)
[+] and that is: @
[+] print provided lines? ([Y]/n)

Samuel Pickwick - pickwick@herot.net
Nathaniel Winkle - winkle@herot.net
Augustus Snodgrass - snodgrass@herot.net
Tracy Tupman - tupman@herot.net
Sam Weller - weller@herot.net
Tony Weller - tweller@herot.net
Estella Havisham - havisham@herot.net
Abel Magwitch - magwitch@herot.net
Philip Pirrip - pirrip@herot.net
Nicholas Nickleby - nickleby@herot.net
Ralph Nickleby - rnickleby@herot.net
Newman Noggs - noggs@herot.net
Wackford Squeers - squeers@herot.net
Thomas Pinch - pinch@herot.net
Mark Tapley - tapley@herot.net
Sarah Gamp - gamp@herot.net
Jacob Marley - marley@herot.net
Ebenezer Scrooge - scrooge@herot.net
Bob Cratchit - cratchit@herot.net
Bill Sikes - sikes@herot.net
Jack Dawkins - dawkins@herot.net
Noah Claypole - claypole@herot.net

[+] can we move on to the next steps? ([Y]/n)
[+] only data (and spaces) must be present in lines
[+] do you want delete some chars? (y/[N]) y
[+] print provided lines? ([Y]/n) n
[+] what can be deleted? -
[+] what type instead that? (empty input will delete it)
[+] print provided lines? ([Y]/n)

Samuel Pickwick  pickwick@herot.net
Nathaniel Winkle  winkle@herot.net
Augustus Snodgrass  snodgrass@herot.net
Tracy Tupman  tupman@herot.net
Sam Weller  weller@herot.net
Tony Weller  tweller@herot.net
Estella Havisham  havisham@herot.net
Abel Magwitch  magwitch@herot.net
Philip Pirrip  pirrip@herot.net
Nicholas Nickleby  nickleby@herot.net
Ralph Nickleby  rnickleby@herot.net
Newman Noggs  noggs@herot.net
Wackford Squeers  squeers@herot.net
Thomas Pinch  pinch@herot.net
Mark Tapley  tapley@herot.net
Sarah Gamp  gamp@herot.net
Jacob Marley  marley@herot.net
Ebenezer Scrooge  scrooge@herot.net
Bob Cratchit  cratchit@herot.net
Bill Sikes  sikes@herot.net
Jack Dawkins  dawkins@herot.net
Noah Claypole  claypole@herot.net

[+] do you want delete some chars? (y/[N])
[+] each line can have data like: NAME, SURNAME, NICKNAME, EMAIL
[+] f.e. line "James Bond 007@mi6.uk" got "NAME SURNAME EMAIL"
[+] does every line contain the same type of data? ([Y]/n) Y
[+] looking on example above, what types of data we have (space between)? name surname email
[+] parsing data...
[+] successfully generated 486 unique usernames
[+] provide filename for output (none for stdout): out.txt
[+] usernames saved to file: out.txt
[+] done! Bye!

