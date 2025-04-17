# caesar-cipher

Lightweight python CLI tool that lets you encode or decode text using a Caesar (letter‑rotation) cipher with customizable shift amounts. The only requirement is __python3__.

# Usages

## Encode
```sh
# rot13 (rotate 13 characters)
caesar "I love tall girls"  
# Output: V ybir gnyy tveyf


# any other (you can use any integer value)
caesar e "I am cheating on my barber!" 34  
# Output: Q iu kpmibqvo wv ug jizjmz!
caesar e "I am cheating on my barber!" -224
# Output: S kw mrokdsxq yx wi lkblob!
```


## Decode
```sh
# rot13
caesar d "V ybir gnyy tveyf" # Output: I love tall girls


# any other
caesar d "Q iu kpmibqvo wv ug jizjmz!" 34
# Output: I am cheating on my barber!
caesar d "S kw mrokdsxq yx wi lkblob!" -224
# Output: I am cheating on my barber!
```

**Default behaviours**
- Any special character (whitespace characters and special symbols) stay as it is
- Cases are not ignored



**links for noobs**

- [How to run a python script](https://realpython.com/run-python-scripts/#:~:text=To%20run%20a%20Python%20script,to%20your%20system's%20PATH%20variable.)
- [Run python script from anywhere (mac, linux)](https://www.samgalope.dev/2023/10/12/how-to-run-python-scripts-anywhere-on-mac-terminal/)
- [Run python script from anywhere (windows)](https://kgleijm.medium.com/run-your-python-scripts-globally-from-anywhere-without-the-full-path-c5b8e1b6c19d)