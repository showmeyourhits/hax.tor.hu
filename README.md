# hax.tor.hu
hax.tor.hu solutions
For 1 - 22 go to: https://github.com/CyrilP/hax.tor

hax.tor
=======
#Level 23
It's hidden under the message on the transparent gif
password -> imagepw

#Level 24
broken

#Level 25
Just need to do bitwise AND
password -> 10000001

#Level 27
Google file signature - FF FE
jpg is actually a mp3
password -> monkey

#Level 29
enter "<<>b<>>lol<<>/b<>><<>script<>>"

#Level 30
Vertical lines shows dividers from 1 to 10. For 100 -> 1, 2, 4, 5, 10. Only first is white, so number must be prime.
Plus signs -> digits. Larger digit - larger sign. They goes in reverse order.
password -> 200551

#Level 31
pattern is "___"
password -> "bla nobody greg test student admin superadmin"

#Level 32
Get file2image.php in image: "file2image.php?file=file2image.php".
Look at the end of the file in hex editor.
Fool regex check by using: .../...//
Get /level32/index.php in image: "file=.../...//index.php".
Hex again, retrieve base64 encoded pass
password -> "lmfao99"

#Level 34
Create chequerwise mask (some color and transparent) and apply to png. You need dino image.
password -> "excuse"

#Level 35
There is only one number but in different numeral systems. (First is 16, second - 15, etc).
password -> "10516620"

#Level 36
Files starting with dot (.htacces, etc) are not displaing.
Get .bash_history and find root password there (search for su).
password -> "indian3"

#Level 37
Search for Uncle Fibo numbers list. Find number #200.
password -> "77189525"

#Level 38
Check file for viruses online.
password -> "bagle"

#Level 40
Search coordinates on google maps. Turn on sattelite view
password -> "fingerprint"

#Level 42
password -> "unifiedweb.net"
