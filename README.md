
#   Tooli

This is a tool build in python script . It contains .
Web recon and Cryptography tools "Commands".

## Authors

- [@disassembles](https://www.github.com/disassembles)

## Deployment

To deploy these Tools run

```bash
  git clone https://github.com/disassembles/tool.git
  
  cd Tooli
  python Web.py
  python Crypto.py
```


## Features

- Time Saviour
- Donot want to remember any tool command now
- Just Copy the command and change url and run
- Specially build for (Ctf player and Bug Hunter)



## Usage
"Same for both Web.py and Crypto.py"
```python
user(Web): tools 
                 OR
user(Crypto): tools

--> Tools present in my tool will preview

user(Web): website

--> Recon website will be preview

- For Tools that previewed using tools command
EXP: 
    user(Web): gobuster
    gobuster dir -u http://example.com -w /usr/share/wordlists/dirb/common.txt -t 50 -o gobuster_results.txt
```



