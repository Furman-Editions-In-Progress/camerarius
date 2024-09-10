## How to review past transcriptions: 
The past transcriptions use the cts urns to identify pages and page areas.  
The folder "data" (https://github.com/Furman-Editions-In-Progress/camerarius/tree/master/data) contains the csv exports of all past transcriptions, which we will migrate onto Transkribus as the project moves forward. 

A CTS URN identifies the edition according to author, edition year, volume and page number. The last two couples of digits identify, for example, 01 = volume 1, 00002 = page 2. You can see all the pages with these numbers at https://github.com/Furman-Editions-In-Progress/camerarius/tree/master under "vol1_thumbs.md" etc.  

To see the scan of the page:   
* Go to Camerarius Text (https://docs.google.com/spreadsheets/d/1xPo3x3bcssHrFTWXTcw08dGe3xXxa9OCOQytn5ICS5Q/edit?usp=sharing), which contains the transcriptions. The first column of the sheet contains a traditional citation identifier, e.g. 1.2.0
* Go to Text to Image (https://docs.google.com/spreadsheets/d/11vJuQE7_oPDrIlFYzqoBMRlDuichan3eDXxsXenBP24/edit?usp=sharing) and look up the specific citation of the text you want. For example, 1.2.0 will be urn:cite2:fufolio:camerarius1668.2020a:01_00004@0.1614,0.1368,0.7652,0.08598. In this string, **01 is the volume number** and **00004 is the page number**
* In order to find that volume and page, you can either go to the [thumbnails]([url](https://github.com/Furman-Editions-In-Progress/camerarius/blob/master/vol1_thumbs.md)) of Volume 1 and look up page 00004, or go to https://www.homermultitext.org/ict2/index.html?urn=urn:cite2:fufolio:camerarius1668.2020a:01_00002 and **replace the volume number (01) and the page number (00004)** with the ones of your URN. You should be able to see the page that was transcribed.
