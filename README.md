Crack a HS256, HS384 or HS512-signed JWT. You need `PyJWT` and `tqdm` for these scripts:

    pip install PyJWT tqdm

## crackjwt.py

    python crackjwt.py <JWT> dictionary.txt

Try to verify the signature on the JWT using all words in `dictionary.txt` (one per line).

## Example
```
python crackjwt.py eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJ1c2VyX2lkIjoxMjMsImV4cCI6MTcyNjQxNDI0Mn0.bYbO0lk3XoqfT1SXBT9pJ5iH1kxsHSdDB6jy2VjVyZY dictionary.txt
```
![image](https://github.com/user-attachments/assets/53db5521-48c8-4fab-a798-e8069675f388)
