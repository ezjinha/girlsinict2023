# Girls in ICT 2022 Hackathon

## PPT link(need to update)<br/>
https://ericsson.sharepoint.com/:p:/r/sites/GirlsinICT2020Hackathon-mentorgroup-GirlsinICT2022-techmentors/_layouts/15/Doc.aspx?sourcedoc=%7B4EA45A6F-84E8-4080-B59C-7D55007A7C0B%7D&file=2022%20Girls%20in%20ICT_training%20day_PA3.pptx&action=edit&mobileredirect=true&cid=dd97475b-ead6-4796-a2a2-cc8cb660351c&PreviousSessionID=7802057c-d910-00fe-e45e-1d760c8495d0


## example code for module<br/>
https://github.com/eleparts/raspi-AdvancedKit


## LED<br/>

### GPIO<br/>
```Bash
# Install GPIO Library
git clone https://github.com/wiringpi/wiringpi
cd wiringPi
git pull origin
./build
pinout
gpio -h
gpio readall

# Turn on LED with pin21
gpio -g mode 21 output
gpio -g write 21 1
gpio readall  //여기서 21번핀이 output으로 바뀌고 v가 1이 되었는지 확인
gpio -g write 21 0
