My Plugins for Notepad++

1. NC-Code Sinumerik:
     Special Thanks to Sergio for this reference GCODE-Sinumerik_bySergioGU.xml from the UDL:
     https://github.com/notepad-plus-plus/userDefinedLanguages
     - Added Folding for Loop programming
     - added various commands for high level NC programming
     - added Highlighting for all Sinumerik Standard Cycles
     - added Highlighting for all Sinumerik Measuring Cycles
     - Syntax Highlighting available now for all listed Operations Chapter 5.1 from NC Programming Manual for SINUMERIK ONE
       https://support.industry.siemens.com/cs/ww/en/view/109974190
       
       Even though SINUMERIK ONE as latest controller for the Sinumerik family is the reference for this project, most, even up to almost all content is also valid for other Sinumerik CNC's such as Sinumerik 840D sl, Sinumerik 828D, Sinumerik MC...
            - All variables with a $ -Dollar Sign up front are considered as System variable or Machine Data
            - All variables with a _ -Underbar Sign up front are considered as Local programmed variables or GUD's defined on the System
     - added Autocompleting for Sinumerik System Variable
  
2. Installation:
    
   Copy NC_CODE_Sinumerik_bySuperfestung.xml file to:
   C:\Users\"YourUserName"\AppData\Roaming\Notepad++\userDefineLangs
   
   Copy "NC-Code.xml" file to:
   C:\Program Files\Notepad++\autoCompletion
   
   Caution: Do not change the name of "NC-Code.xml", it is related to the coding language in NotePad++
4. Features:
   
Before Installation:
![image](https://github.com/user-attachments/assets/0f936a18-379e-44ed-8db0-5487e46850f0)

After Installation:

![image](https://github.com/user-attachments/assets/18b9ef06-d11a-4261-a1e8-1af49633aa66)


Code Folding:

![image](https://github.com/user-attachments/assets/3ac4b12a-ac13-4396-8d3f-7d63d56b9e92)


Cycle Parameter Support:

![image](https://github.com/user-attachments/assets/b1a738a3-c31f-4ef2-8c6f-2f8592c7a829)

![image](https://github.com/user-attachments/assets/98ac45f4-0819-488a-86fb-5a3155197a14)

![image](https://github.com/user-attachments/assets/f3dd34ab-3b91-4655-938d-8e6726270fb1)

Grinding Cycles:

![image](https://github.com/user-attachments/assets/ed2cd3f6-e199-4464-b73f-f02aa11328c8)

![image](https://github.com/user-attachments/assets/c615d6ed-87b4-4602-a4b2-9391a6f1e583)

Measuring Cycles:

![image](https://github.com/user-attachments/assets/4f990117-9ee6-46f9-8215-de0c7f29f054)



Restrictions and Limitations:
- After Loading the Autocompletion File, it might take a while until the autocomplete highlight text is visible!
- Todos:
     - Shorten Description to e.g. 100 charcters, continue on new line
     - Shorten Paramter Sisplay to e.g. 100 charcters, continue on new line
     - Check and remove of special charcters
     

Further Ideas:
- Read in GUD's and Macros by a import function
- Auto complete of NC Code including Paramters
- Context Sensitive Help on e.g. Mouse over or Button Pressed
- Variable Picker
- Menu for Sinumerik
     - Start for Create MyVirtual Machine
     - Access to virtual SD-Card
     - Create a Project Folder
     - Start for WinSCP
     - Start for Access MyMachine P2P
     - Import Logfiles
     - Import Cycles, Screen-Files
 - Run MyScreen Languege Highlighting
 - Inifiles Highlighting
 - ...

  Send Feedback to superfestung@icloud.com 
