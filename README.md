# windows-product-key-extractor
I found this script on the Internets and refined it a bit with ChatGPT since im not going to code in vbs anytime soon. Please check the script first before running it. 

**Note:** that this program is intended for educational or informational purposes only and should not be used to violate any software license agreements.

This VBScript program retrieves the product key for the installed copy of Microsoft Windows on your computer. It uses the Windows Registry to read the product key and then displays it in an input box for you to copy or use.
How to Run the Program


* Double-click the saved .vbs file to run the program.
* An input box will appear displaying the extracted product key for your Windows installation. You can copy or use the product key as needed.

## Script Details

The script uses the WScript.Shell object to create an instance of the Windows Shell, which is used to read the product key from the Windows Registry. The extracted key is then passed to the ConvertToKey function, which converts the binary key data into the standard 25-character product key format. Finally, the product key is displayed in an input box using the InputBox function.

**Note** that this program is intended for educational or informational purposes only and should not be used to violate any software license agreements.
