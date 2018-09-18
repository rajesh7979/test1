# test1
#app to db conncetivity
#bin bash scripts
#!/bin/bash
DB1=$(telnet @hostname@ portnumber <2/dev/extension | awk "{print$2}")
echo $echo
if [$? ==0]
echo -e" print connected"
then:
echo -e " not connected"
