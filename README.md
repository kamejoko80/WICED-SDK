/*
* @copyright Copyright (c) 2012-2015 RedBearLab
*
* Permission is hereby granted, free of charge, to any person obtaining a copy of this software 
* and associated documentation files (the "Software"), to deal in the Software without restriction, 
* including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, 
* and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, 
* subject to the following conditions:
* The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.
*
* THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, 
* INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR 
* PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE 
* FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, 
* ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
*/

-------------------------------- Usage --------------------------------

1. Download Broadcom WICED-SDK-3.3.1 from : http://community.broadcom.com/docs/DOC-2312

2. Unzip WICED-SDK-3.3.1 to your local file-system

3. Merge the WICED-SDK-3.3.1 in the patch with the WICED-SDK-3.3.1 you just unzip and replace the original files

4. Go to ST official website to download and install the st-link driver (For Windows Only, OSX doesn't need)
- http://www.st.com/web/en/catalog/tools/PF260219

5. Open the command line terminal and change the working directory to WICED-SDK-3.3.1>

6. Type in "make rbl.rgb-RB_Duo download JTAG=RBLINK run" and press the Enter on the keyboard to begin build the project
   that under the folder "WICED-SDK-3.3.1\apps\rbl\rgb". More details about make usage please refer to the Makefile which under 
   "WICED-SDK-3.3.1\"

