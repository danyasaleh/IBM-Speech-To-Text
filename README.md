# IBM-Speech-To-Text
The task about how to convert a real time speech to text and store the text 

1- I work with IBM cloud and select the service ( Speech To Text )
2- setup the apikey and region inside speech.cfg
3- install the requierment that is inside requirements.txt file  by type    ( pip install -r requirements.txt )
4- run the python code transcribe.py   by write   ( python transcribe.py -t 5 )  -t = time to record   5= 5 seconds

After that save the text in .txt file :

so to do this I add the code below to transcribe.py page 

 outfile= open('outputs.txt', 'w')
 outfile.write(data['results'][0]['alternatives'][0]['transcript'])
 outfile.close()
 
 The outputs.txt : will show the text that was recording
 
 The Real time speech to text.png : photo show the recording speech
 
 
