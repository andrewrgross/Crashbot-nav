# Crashbot-nav

Crashbot is a ROS robot built on a Roomba 595 base. This repo contains files that the Navigation Stack uses.  Details on this project can be found here: https://crashbot.atlassian.net/l/c/xM3gXxR4

Details about each of these file types can be found below.

RViz configuration files contain a list of topics RViz is publishing and subscribing to and other parameters about what elements to display in RViz:
https://answers.ros.org/question/11845/rviz-configuration-file-format/

PGM files are Portable Grey Map files. These are text-readable rastor image files. They're an array from 0 to a specified value that score each pixel on how confidently a system believes that location on the map to be vacant.
https://subsurfwiki.org/wiki/Portable_gray_map

The YAML file is a metadata file that the map_server uses to load a map. It specifies a PGM file and then declares what distance scale each pixel in the PGM describes.
http://wiki.ros.org/map_server
https://answers.ros.org/question/42782/mapyaml-format/
