# DISCOVERY-PLUS-YTDLP
**Bash Scripts To Bulk Download Episodes From Discovery+**


```bash
#######################################################################################################################
#######################################################################################################################
########################                    WARNING: Use wisely and what not..                #########################
#######################################################################################################################
#######################################################################################################################
#######################################################################################################################
###              /$$$$$$$  /$$$$$$$$  /$$$$$$  /$$$$$$$        /$$$$$$$$ /$$   /$$ /$$$$$$  /$$$$$$                 ###
###  ;;;;;      | $$__  $$| $$_____/ /$$__  $$| $$__  $$      |__  $$__/| $$  | $$|_  $$_/ /$$__  $$         ;;;;;  ###
###  ;;;;;      | $$  \ $$| $$      | $$  \ $$| $$  \ $$         | $$   | $$  | $$  | $$  | $$  \__/         ;;;;;  ###
###  ;;;;;      | $$$$$$$/| $$$$$   | $$$$$$$$| $$  | $$         | $$   | $$$$$$$$  | $$  |  $$$$$$          ;;;;;  ###
###  ;;;;;      | $$$$$$$/| $$$$$   | $$$$$$$$| $$  | $$         | $$   | $$$$$$$$  | $$  |  $$$$$$          ;;;;;  ###
###  ;;;;;      | $$__  $$| $$__/   | $$__  $$| $$  | $$         | $$   | $$__  $$  | $$   \____  $$         ;;;;;  ###
###..;;;;;..    | $$  \ $$| $$      | $$  | $$| $$  | $$         | $$   | $$  | $$  | $$   /$$  \ $$       ..;;;;;..###
### ':::::'     | $$  | $$| $$$$$$$$| $$  | $$| $$$$$$$/         | $$   | $$  | $$ /$$$$$$|  $$$$$$/        ':::::' ###
###   ':`       |__/  |__/|________/|__/  |__/|_______/          |__/   |__/  |__/|______/ \______/           ':`   ###
#######################################################################################################################
#######################################################################################################################
##                              ---> IF THESE SCRIPTS ARE NOT WORKING FOR YOU... <---                                ##
##                     THERE'S A HIGH LIKELYHOOD THAT YOUR COOKIE ISN'T FORMATTED CORRECTLY                          ##
#######################################################################################################################
#######################################################################################################################
##                   ---> I HIGHLY RECOMMEND USING CHROME WITH THE EditThisCookie EXTENSION: <---                    ##
##           https://chrome.google.com/webstore/detail/edit-this-cookie/fngmhnnpilhplaeedifhccceomclgfbg             ##
#######################################################################################################################
#######################################################################################################################
##                               YOUR COOKIE FILE NEEDS TO BE IN NETSCAPE FORMAT ONLY                                ##
##                            YOU MUST INCLUDE ALL Discovery+ SUB-DOMAINS IN YOUR COOKIE                             ##
#######################################################################################################################
#######################################################################################################################
```

## UPDATE: There are TWO Versions of The Script Now..

**[ALL SEASONS] DISCOVERY_PLUS-YTDLP:**  
Use this version if you want to download ALL episodes from ALL seasons

**[SINGLE SEASON] DISCOVERY_PLUS_SS-YTDLP:**  
Use this version if you want to download ALL episodes from ONLY ONE SPECIFIC SEASON

### Requirments:
**SED**  
https://www.gnu.org/software/sed/manual/  
**YT-DLP**  
https://github.com/yt-dlp/  
**JQ**  
https://stedolan.github.io/  
**ARIA2C**  
https://aria2.github.io  

### How do these scripts work?
- These scripts will prompt you for the series url on Discovery+, then your cookie file, then your working directory for output...  
- **DEPENDING ON WHICH VERSION OF THE SCRIPT YOU USE** it'll then automatically grab all episodes from either all seasons or a single season...  
- It'll then use yt-dlp/aria2c to multi-thread download all of the episodes.  
- Discovery+ episode files have a shit ton of fragments, so the merging of each episode will take some time.  
- You'll notice this when aria2c seems to be paused, but really it's just merging the files in the background.  

### Here's a demo using the **DISCOVERY_PLUS_YTDLP** script version (Which downloads ALL seasons):
<p align="center">
  <a href="#"><img width="560" src="https://gist.githubusercontent.com/ohmybahgosh/319c129840bc0804bb4f1a468abb90f1/raw/c868afc3389df34c92476c61edc249d3f122d5fb/YT_SCRIPTS.svg"></a>
</p>

### Note from OhMyBahGosh:
- These are my personal scripts that I've cobbled together for my own servers...I've done a shit job cleaning them up enough for public usage, but it gets the job done.  Feel free to submit pull requests, as I'm sure there are improvments to be made.  
- I haven't had the time, but the end game here is to merge these two scripts in to a single script with functions...but, I have no idea when I'll get around to it.


