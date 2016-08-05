#Atom in the Batcave
##100 things to know about Atom.io the Github code editor

As an avid Sublime Text user it took me some time to make the move to Atom. I was just too attached to my shortcuts and dozens of code snippets that I had written over the years. I finally made the move to Atom after completing the (Tutsplus course on speedy workflows in Atom)[https://code.tutsplus.com/courses/speedy-workflows-with-atom?ec_promo=teaser_post].

###Here are 100 things that you need to know about the free Github editor, atom.io

1. Download atom at atom.io
2. Command O - open a project
3. Command N - new tab
4. Control Command F - Full screen
5. Command Option - left or right tab through projects
6. Command , - change settings
7. Shift Command P - All the shortcuts
8. Install theme - Command comma, Install, Themes, Monokai (Kevinsawicki), Monokai-Seti, Themes - UI theme - seti, Syntax theme - Monokai-Seti.
9. Command B - all files in the buffer (files that are currently open)
10. Command P - find all files
11. Command D - Highlights many instances - incremental search
12. Control Command G - All of the command Ds at once
13. Sublime style column select - INSTALL sublime-style-column-selection - now we can alt select up or down
14. Panes - Command K (lift the keys and then)(up, down, left, right)
15. Snippets - Perform regular tasks quickly and easily
16. Snippets are written in coffee script (CSON), to create one type Shift command P and open your snippets, then type snip and tab
17. Write your snippet like this:
    ```
    ".source.js":
      "Google analytics":
        "prefix":"ga"
        "body":"""(function(i,s,o,g,r,a,m){i['GoogleAnalyticsObject']=r;i[r]=i[r]||function(){
            (i[r].q=i[r].q||[]).push(arguments)},i[r].l=1*new Date();a=s.createElement(o),
            m=s.getElementsByTagName(o)[0];a.async=1;a.src=g;m.parentNode.insertBefore(a,m)
            })(window,document,'script','//www.google-analytics.com/analytics.js','ga');
            ga('create', '${1:UA-1615344-7}', {'allowAnchor': true});
            ga('send', 'pageview', {
            'page': location.pathname + location.search  + location.hash
        });"""
    ```
18. To set variables in snippets either use $1 or ${1:defaultname}
19. Github integration will show you how your files appear on Github.
20. Switching between Github and Atom
