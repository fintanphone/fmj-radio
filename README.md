End result should be Radio Streaming on a LyraT ESP32 Audio Board.

In this first phase creating an ESP32 hosted webpage which will be used to select and play favourite stations.

Initially station list will be stored and maintained in a .csv file on the micro SD card. Playlist will be 
presented on the web site.

To view work in progress page:

Build using IDF version 4.3 (To be adapted to 4.1). After flashing run idf.py -p /dev/ttyUSB0 monitor (on Linux)
Reset the board and take note if ip address assigned. 
