# kiruna-blasting
Seismography experiment - underground iron mine blasting detection by smartphones. 

Every night in Kiruna iron ore mine the tons of explosives are blasted betwen 1:15 and 1:40 local time. The most usual time for blasting is 1:30. 
If you stand near to Kiruna LKAB mine in that time you definitely feel the artificial earthquake generadet by explosion around one kilometer bellow surface. 

You can hear the sound recording of the blasting by playing one of [these files](https://github.com/geozor-network/kiruna-blasting/tree/master/data/16092019/kakl). (But you definitely need a subwoofer to hear something) 

The movements are so intensive that they could be measured by generic smartphone accelerometer sensor.


![Blasting induced earthquake in Kiruna iron mine](/doc/img/seismograph.png "Seismogram plotted from accelerometer sensor")

As you can see from the plotted data above, explosion generated shaking is clearly visible. 

For the data recording the AndroSensor application was used. The sampling period was configured to 20 ms.

The most challenging issue in the experiment is precise time synchronization between the smart-phones even in case of GPS fix (Android is unable to automatically correct ) 


![Time inconsistenci of the phones](/data/16092019/Phone_time_unsync.JPG "Different time at each phone used")


Full recording is out of github file size limit. Therefore it is available upon request. 
