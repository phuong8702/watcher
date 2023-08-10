
How to obfuscate code by pyarmor:

1. Install pyarmor: pip install pyarmor

2. Check if it was successfully: 'pyarmor' or 'pyarmor --version'
    if the output is: pyarmor: command not found
    fix by: export PATH=$PATH:~/.local/bin 

3. Obfuscate code: pyarmor obfuscate your_script.py
    Folder 'dist' have generated. It contains code file has been obfuscated and run code as usual