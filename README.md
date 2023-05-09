#

### generate secret key
#### Mtd 1
(jwt) alvinlim@coolhandsg-iMac jwt % python
Python 3.9.2 (default, Dec  7 2021, 20:32:07) 
[Clang 13.0.0 (clang-1300.0.29.3)] on darwin
Type "help", "copyright", "credits" or "license" for more information.
>>> import os
>>> os.urandom(12)
b'\x80\x0cA\xaaC\xbc\xb6$\x1f\xe4\x98\xef'

## requirements
### to create the file
$ pip freeze | grep -i fastapi >> requirements.txt  //grep is a shell cmd

### extract from requirements.txt
pip install -r requirements.txt
