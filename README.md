Crack a HS256, HS384 or HS512-signed JWT. You need `PyJWT` and `tqdm` for these scripts:

    pip install PyJWT tqdm

## crackjwt.py

    crackjwt.py JWT dictionary.txt

Try to verify the signature on the JWT using all words in `dictionary.txt` (one per line).
