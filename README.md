   ____ ____ _____  ____  _                       
  / ___| __ )__  / |  _ \(_)_ __  _ __   ___ _ __ 
 | |   |  _ \ / /  | |_) | | '_ \| '_ \ / _ \ '__|
 | |___| |_) / /_  |  _ <| | |_) | |_) |  __/ |   
  \____|____/____| |_| \_\_| .__/| .__/ \___|_|   
                           |_|   |_|             

Hey there!

    Cbz ripper is a small script that automates downloading images sequentially from MangaLife and
    converting them into the cbz archive format. I decided to write this script after going through
    the tedious task of trying to do what I just described manually. It's far from impossible, of
    course, but it is extremly monatonous and it leaves room for human error.

    The main mechanism by which this script functions is by iterating through through a url, downloading
    theimage that it leads to, editing the url to proceed to the next page, and repeating the process. This
    requires you to provide location on where the page and chapter indexs are located within the url so
    the program knows where to look when it's iterating. (Think slice notation if you have a passing
    familiarity with python.)

    Yeah I know. It's ugly, hacky, and ineffcient as all hell but it gets the job done. This script was
    originally designed for a specifc manga site, but it could theoretically work with any seires of
    images as long as the pages and chapters aren't uniqually named in the url.

    And look. This script can operate in a bit of legally grey area (because so do all manga scan sites,
    so I'll counsel as follows: while I wish that everyone could read the wealth of amazing content that
    humans have produced, artists need to be compensated for their work. Obviously I can't control what
    you will do with this script, but I hope that you recognize that fact and support those who produce
    content you enjoy. Even if it's just a hard copy of your favorite issue, it's something.

    Happy reading!
# CBZ_Ripper
