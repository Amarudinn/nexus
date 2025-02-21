## Windows

1. Clone repository
```bash
git clone https://github.com/Amarudinn/nexus.git
cd nexus
```

2. Edit file .env

3. Edit address.txt masukan address penerima 

4. Install dependencies
```bash
pip install requirements.txt
```

5. Run script
```bash
python multisend.py
```


## Linux/VPS

1. Clone repository
```bash
git clone https://github.com/Amarudinn/nexus.git
```

2. Buat screen
```bash
screen -S nexus-multisend
```

3. Open file
```bash
cd nexus
```

4. Edit file .env
```bash
nano .env
```

5. Edit address.txt masukan address penerima
```bash
nano address.txt
```

6. Buat enviroment
```bash
python3 -m venv venv
source venv/bin/activate
```

7. Install dependencies
```bash
pip install requirements.txt
```

8. Run script
```bash
python3 multisend.py
```
