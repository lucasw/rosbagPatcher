# ROSBAG TCPROS HEADER FIX

This script fixes bag files with broken header data by skipping the erroneous messages. This script might help you if you are experiencing an error similiar to:
> [ERROR] [1370268742.143131348]: Received an invalid TCPROS header.  Each line must have an equals sign.
> [FATAL] [1370268742.143399219]: Error parsing header

## Usage:
> rosbagPatcher.py [sourceBagFile] [destinationBagFile]
