# Guide on how to use tags on Camerarius

Note: Pages 14 and 15 have been set as **Ground Truth**, they should be used as examples on how to use the tags. See [them here](https://app.transkribus.eu/share/029c643deedd895dd8a7c7d3ac3bb4b4)


### Structural Tags

The following structural tags are actively used in Camerarius: 

* heading: for headers, titles, and anything that is extra-textual. 
* caption: for all captions of emblems. 
* catch-word
* marginalia
* footnote
* image: for all emblems

### Textual tags

* **abbrev**: for abbreviations. By default, we do not expand abbreviations in the transcription and transcribe the word as it appears. We record the expanded word under "expansion" in the tag.
<img width="407" alt="image" src="https://github.com/user-attachments/assets/85ec8a53-909f-4457-8486-0bccbc35ea1a" />

* **work**: a work title being cited, referenced or quoted by Camerarius. The best known title can be recorded under "title", as well as the "author" (especially if not explicitly mentioned in the text). The WikiDataID can be used for identification.
<img width="384" alt="image" src="https://github.com/user-attachments/assets/19187312-c0ec-43cf-bbe0-ebefe81b3351" />   

* **unclear**: whenever something in the transcription requires double-checking. Record alternative options under "alternative", and comments under "comment".

![image](https://github.com/user-attachments/assets/2fb1b2cf-0417-4bd8-9db0-deafa52b1f15)     

* **date**: date and time periods    
  
* **person**: any personal name except Camerarius. Under "name", indicate the best-known name. If the person is an author, record "author" under "type". WikiDataID can be used for further identification.

![image](https://github.com/user-attachments/assets/625e0503-717a-486e-a680-4ff799b3d496)   

* **place**: any place mentioned. Record the best-known placename under "placeName", and use Pleiades (https://pleiades.stoa.org/) or WikiData for better identification.
  
* **scope**: use this tag for any mention of a location in a work, e.g. chapter number, paragraphs, anything that refers to a work but is _not_ a title. For example, "Quintilian, De Inst. caput 2 vol. I": Quintilian = person.author; De Inst. = work; caput 2 vol. I = scope. You may record a clearer version under "work" in the scope tag: in this case, for example, "De Institutiones 1.2".
<img width="388" alt="image" src="https://github.com/user-attachments/assets/8779b8cc-6ce8-4a2f-a18e-6bbfa996b966" />


* **quotation**: any literal quotation or citation from another work.   
![image](https://github.com/user-attachments/assets/8e843202-7f9f-4c6a-80ec-f379eaf9e51f)   

If you are able to find the original text of a quotation online, make sure to record the exact citation reference. If you can find it in Scaife (https://scaife.perseus.org/), record the CTS URN under "URI":   
![image](https://github.com/user-attachments/assets/1c0338a4-73d0-47b9-bc5b-7e253469adc3)
  


