# Level 0-1 code - boJ9jbbUNNfktd78OOpsqOltutMc3MY1
# Level 1-2 code - CV1DtqXWVFXTvM2F0k09SHz0YwRINYA9
# Level 2-3 code - UmHadQclWmgdLOKQ3YNgjWxGoRMb5luK
# Level 3-4 code - pIwrPrtPN36QITSp3EQaw936yaFoFgAB
# Level 4-5 code - koReBOKuIDDepwhWk7jZC0RTdopnAYKh
  used file -- * to show the content in the files
  also used cat and the full directory to display the code
# Level 5-6 code - DXjZPULLxYr17uwoI01bNLQbtFemEgo7
  to find the human readable file with 1033 in size and non executable, had to use the following command:
find . -type -f -size 1033c ! -executable
! = means not
c means bytes
# Level 6-7 code - HKBPTKQnIay4Fw76bEy8PVxKEDQRKTzs
The password for the next level is stored somewhere on the server and has all of the following properties:

    owned by user bandit7
    owned by group bandit6
    33 bytes in size
  used find command with / to search the entire directory
  find / -type f -user bandit7 -group bandit6 -size 33c
  type -f = file
  searched by user bandit7
  group by bandit6
  and size 33 bytes
# Level 7-8 code - cvX2JJa4CFALtqS87jk27qwqGhBM9plV
  used cat and grep command
# Level 8-9 code - UsvVyFSfZZWbi6wgC7dAFyFuR6jQQUhR
 used the sort and uniq command to find the code occurring once
 sort data.txt | uniq -c = uniq shows the string that shows the count number as well
# Level 9-10 code - truKLdjsbJ5g7yyJ2X2R0o3a5HQJFuLk
 used strings command and grep "=" to find text with = preceding it 
 strings data.txt | grep "="
# Level 10-11 code - IFukwKGsFW8MOq3IRFqrxE1hxTNEbUPR
 copied the text from the file and decoded it using base64 site
 or use the base64 command
# Level 11-12 code - 5Te8Y4drgCRfCx8ugdwuEX8KFC6k2EUu
 ran the text of the data file in a rot13 site
# Level 12-13 code - 8ZjyCRiBWFYkneahHwxCv3wb2a1ORpYL
# Level 13-14 code - 4wcYUJFw0k0XLShlDzztnTBHiqxU3b3e
# Level 14-15 code - BfMYroe26WYalil77FoDi9qh59eK5xNr
# Level 15-16 code - cluFn7wTiGryunymYOu4RcffSxQluehd
 used the s_client command
# Level 16-17 code - used rsa code after finding ssl connection
# Level 17-18 code - kfBf3eYk5BPBRzwjqutbbfE887SVc5Yd
 - used diff
# Level 18-19 code - IueksS7Ubh8G3DCwVzrTd8rAVOwq3M5x
 used -t and bin/sh to enter
# Level 19-20 code - GbKksEFF4yrVs6il55v6gwY5aVje5f0j
 -do it
# Level 20-21 code - gE269g2h3mw3pwgrj0Ha9Uoqen1c9DGr
 setup nc on listening port first
# Level 21-22 code - Yk7owGAcWjwMVRwrTesJEwB7WVOiILLI
 checked cron file
# Level 22-23 code - jc1udXuA1tiHqjIsL8yaapX5XIAI6i0n
 use shell
# Level 23-24 code - UoMYTrfrBFHyQXmg6gzctqAwOmw1IohZ
 created sh
# Level 24-25 code - uNG9O58gUE7snukf3bvZ0rxhtnjzSGzG
 created brute shell
# Level 25-26 code - 5czgV9L3Xx8JPOyRbXh6lQbmIOWvPT6Z
 forced terminal through ssh 
# Level 26-27 code - 3ba3118a22e93127a4ed485be72ef5ea
 entered shell within more sh
# Level 27-28 code - 0ef186ac70e04ea33b4c1853d2526fa2
 used git clone for code
# Level 28-29 code - bbc96594b4e001778eee9975372716b2
 git clone and log and checkout
# Level 29-30 code - 5b90576bedb2cc04c86a9e924ce42faf
 git branch -r and checkout 
# Level 30-31 code - 47e603bb428404d265f59c42920d81e5
 git tag
# Level 31-32 code - 56a9bf19c63d650ce78e6ec0354ee45e
 git push after making key text
# Level 32-33 code - c9c3199ddf4121b10cf581a98d51caee
 converted to bash shell
