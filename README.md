JQuery Local Ajax
=========
I got many ppl asking for reading local file.
there are several ways. one is Jquery <element>.load(file). ie $('#menuitems').load('thismonthmenu.html#entree'); or
javascript ajax.get.
Can also do java io class, read file byte per byte. I tried this way for bin files only.

The src of this app actually submitted as commercial app in GGplay, Appstore, BB for ...hmm...0.99 buck :-(.
https://itunes.apple.com/us/app/1001-jokes/id698098510
https://play.google.com/store/apps/details?id=mobi.intcloud.jokes

-it uses only JQuery, no other plugin, for touch device, bind (touchup) on body, detects touch position, 
right = e.currentXpos > screen.width/2. left -> prev page, right-> next page.

-The app lets user select a book (txt file), load it in a screen size box -one paragraph a time-, if the overflow triggers, then the content of the page is push into an array, clear the box, and repeat the loop until end of the file.

-The first page in the array then be displayed in the box waiting for user touch or click to show next or prev page.

-The current page index is stored in localstorage, so next time app loads will be in last reading page.

There are several steps to use the code:
1-Remove the copyright page ;-), or change it into yours.
2-Apply Jquery Mobile and Jquery UI for better presentation. I didnt use them then bc their earlier versions seem having rather unstable behaviour on Android and BB. Will try again when I have time, again only 0.99 buck.

issues:
1-lack of comments, as u can see, most of my apps are only few days work done during my weekend or on train to work -I work fullime-, therefore, cannot expect fully commented. I stopped being a lecturer long time ;-).
2-spelling error, I read/write 5 languages. Eng spelling is the worst.
3-expression funny, yeap, I know it too. 
4-in short, can pop me a question or two. Dont promise to reply right away. Beside of working on my 4 computers (Win8/Imac/Linux x2), I am also running a parenting job.
