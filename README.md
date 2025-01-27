# Background
The data team wanted to make an enhanced report card to be distributed to each student at the high school during midquarter conferences. Tableau was the most convenient visualization tool for the charts and tables I had in mind, and I could add a parameter to show data for any given student, but it would take a long time to flip through everybody and print them one by one.

After some research, I found the command line tool ```tabcmd```, which can access a Tableau server and download pages from workbooks. By making the student parameter a part of the requested URL, I could write code to export reports at scale. The first version was a .bat script, but the next quarter I switched to interactive python.
