# PLEX TV SHOW RENAMER

I made this to organize plex files properly, as I was tired of doing it manually.

# How it works

1. Make sure your files are in order, and in their correct folder
2. Follow: https://support.plex.tv/articles/naming-and-organizing-your-tv-show-files/ \
  2a. ShowName/Season 1,2..3..n
3. Run this script
   *   The code automatically will check the old file name filetype before converting the name that way the mkv, or mp4 stay the same
   *   Logging: In the show main folder you will find a "rename_log.txt" this will keep track of everything that was renamed, this is great when you've misplaced a file
     *  Logging is deleted every new run for that show.   

## Example Run:
   *   [Enter] to continue, 'exit' to quit.
   *   Directory: C:\Users\Casterial\Downloads\ExampleShow
   *    Finished Renaming Season 1
   *    Finished Renaming Season 2
   *    [Enter] to continue, 'exit' to quit.

## Logging:
********Renaming Season 1********\
* Renamed: EP191.mp3 to ShowExample_Season 1_01.mp3\
* Renamed: EP192.log to ShowExample_Season 1_02.log\
* Renamed: EP193.mkv to ShowExample_Season 1_03.mkv\
* Renamed: EP194.mp4 to ShowExample_Season 1_04.mp4\
* Renamed: EP195.txt to ShowExample_Season 1_05.txt\
********Renaming Season 2********\
* Renamed: EP191.mp3 to ShowExample_Season 2_01.mp3\
* Renamed: EP192.log to ShowExample_Season 2_02.log\
* Renamed: EP193.mkv to ShowExample_Season 2_03.mkv\
* Renamed: EP194.mp4 to ShowExample_Season 2_04.mp4\
* Renamed: EP195.txt to ShowExample_Season 2_05.txt

