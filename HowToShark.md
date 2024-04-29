## How to WireShark
- 'Capture' is the real filter of capture, the one in top bar is a 'visual filter'.
- *HOW TO START*
    click on a nw -> click of the 'shark_fin' (left-top) 
    '//promiscuos mode//' (see traffic!)
- *COLUMNS (Top Interface)*
    'No.' = number of frame capture by WS;
    'Time' = time interval from when capure started and when frame has been captured;
    'Source' =  src MAC address (in this network);
    'Destination' = src MAC address (in this network);
    'Protocol' = MAC protocol;
    'Info' = various info like SSID (name of net analyzed);
- *BOT_LEFT INTERFACE*
    specific info about net
    'Present flags / flags' how chip radio interpretes data
      ->'flags':
        ...
        WEP = a simple crypting alg.
        ...
    'DTIM' used to momentairly turn off radio reciving (if not waiting a msg) to save battery    power
- *BOT_RIGHT INTERFACE*
    msg in exodecimal (on right ascii translation)
