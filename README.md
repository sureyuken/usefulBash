# usefulBash
collection of useful bash commands

send message or data to specific port of given IP, port 99
# nc -w 3 192.168.1.19 99 < [data or text file]

listen to activity at specified port 99 and execute command [echo]
# nc -l 99; if [ $? -eq 0 ]; then echo "Knock, knock!"; fi
