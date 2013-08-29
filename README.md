festival
========

History of my work with Festival TTS related software.

Install (festival and speech_tools):
  1. Download all files from: http://www.cstr.ed.ac.uk/downloads/festival/2.1/
  2. Unpack them into two directories: './festival' and './speech_tools'. All voices and lexicons should be unpacked into './festival' folder.
  3. In './speech_tools": ./configure && make 
  4. In './festival': ./configure && make && make test

Testing:
  1. Run: ./festival/bin/festival
  2. Enter: ```(SayText "Hello World!") (intro)```

Install (festvox):
  1. Download festvox-2.1-release.tar.gz from http://festvox.org/download.html
  2. Unpack into './festvox' folder
  3. In './festvox' run ```./configure && make``` (path to the festival and speech_tools is determined automatically by './configure') 
  


