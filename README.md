# pywin32-bin
NVDA's pywin32-bin dependency 

This repository fulfils NVDA's dependency on pywin32.
It was created using the following steps:

1. Create a new directory.

1. In the new dirctory, execute the following command: `pip3 install -t ./ pywin32`

1. Copy the following dirctories and files from the populated directory to the root of this repository:

	* All files from the root of the `win32` dirctory
	* All files from the `win32/lib` dirctory
	* All files from the `pywin32_system32` dirctory
	* The complete `win32com` dirctory
	* The complete `win32comext` dirctory
	* The `pythoncom.py` module