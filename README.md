# AdvanceKeylogger
## How it works
- Creates a directory to temporarily store information to exfiltrate
- Gets all the essential network information -> stores to log file  (takes about a minute in a half)
- Gets the wireless network ssid's and passwords in XML data file
- Retrieves system hardware and running process/service info
- If the clipboard is activated and contains anything -> stores to log file
- Browsing history is retrieved as a JSON data file then dumped into a log file
- Then using multiprocessing 4 features work together simultaneously:   (set to 5 minutes for demo but timeouts and ranges can be adjusted)
  1. Log pressed keys
  2. Take screenshots every 5 seconds
  3. Record microphone in one minute segments
  4. Take webcam picture every 5 seconds
- After all the .txt and .xml files are grouped together and encrypted to protect sensitive data
- Then by individual directory, the files are grouped and sent through email by file type with regex magic
- Finally, the Log directory is deleted and the program loops back to the beginning to repeat the same process
## Compiled all the code into .exe file for execution.
 -  It renames itself as abs_Flash.exe and also uses adobe icon so it disguise itself as an flash update.
 ![image](https://user-images.githubusercontent.com/67306442/175810909-bc4751ab-15ac-485f-b07a-95b17b740c41.png)

## Demo video:
- https://drive.google.com/file/d/1d4CRby5e_GSU1exUNxSl5YZgpL9-NZpT/view

![image](https://user-images.githubusercontent.com/67306442/174436866-a759feca-2efb-4289-ab00-05502d62a18d.png)
![image](https://user-images.githubusercontent.com/67306442/174436902-7be77b1d-1313-4c8e-a2d3-e30e477df297.png)
![image](https://user-images.githubusercontent.com/67306442/174436924-28eeb002-b784-4b6c-b44e-15a98112d5d4.png)
![image](https://user-images.githubusercontent.com/67306442/174436931-24344a99-56ce-44eb-86c4-fe1e693c603c.png)
![image](https://user-images.githubusercontent.com/67306442/174436938-f5fc6d14-577e-4eb0-8f29-813022254997.png)
![image](https://user-images.githubusercontent.com/67306442/174436942-741e80d3-b832-48ae-a2ea-bb592505b2c9.png)
![image](https://user-images.githubusercontent.com/67306442/174436947-6ff24d49-0dd4-435b-87b6-48274d764a99.png)
![image](https://user-images.githubusercontent.com/67306442/174436951-4e7f42b2-1245-433c-ad0d-9b050138922c.png)
![image](https://user-images.githubusercontent.com/67306442/174436959-7c6e4615-3b2b-4d2b-a5b8-ef1e91a202b0.png)
