# I WANT SCRAPPING AND READ IT LOCALLY 

## BUILD VIRTUAL ENV
```bash
cd python
virtualenv .
```

## ACTIVATE THE VENV
```bash
➜  scrapping-project git:(master) ✗ source python/bin/activate
(python) ➜  scrapping-project git:(master) ✗ cd python/src 
(python) ➜  src git:(master) ✗ 
```

## INSTALL PIP LIBRARIES
```bash
cd src/
pip install -r requirements.txt
```

## I HAVE A SHORTCUT AT 
python/src i have shortcut link to website/image & the name is image-website-shortcut
```bash
➜  src git:(master) ✗ ln -s ../../website/image image-website-shortcut 
```

## USE GIT-PUSH.SH
```bash
chmod +x ./git-push.sh
```
## FOR THE WEBSITE DONT FORGET 
```bash
npm install
```

## PYTHON TO EXE
```bash
pyinstaller --noconsole --onefile main.py
```

## GUI PYTHON TO EXE
```bash
auto-py-to-exe
```