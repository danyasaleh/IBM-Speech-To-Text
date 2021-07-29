# IBM-Speech-To-Text

 
 
 # The task about how to convert a real time speech to text and store the text 
 
 

* I work with IBM cloud and select the service ( Speech To Text )

* setup the apikey and region inside speech.cfg

* install the requierment that is inside requirements.txt file  by type    ( pip install -r requirements.txt )

* run the python code transcribe.py   by write   ( python transcribe.py -t 5 )  -t = time to record   5= 5 seconds





### After that to save the text in .txt file :

so to do this I add the code below to **transcribe.py page**

` outfile= open('outputs.txt', 'w')`

 `outfile.write(data['results'][0]['alternatives'][0]['transcript'])`

 `outfile.close()`



 
**The outputs.txt :** file shows the text that was recording
 
**The Real time speech to text.png :** photo shows the recording speech when I was talking
 
 
