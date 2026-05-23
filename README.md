cd src/
git clone git@github.com:twekberg/csvviewer.git
cd csvviewer
python -m venv venv
dos2unix venv/Scripts/activate
source venv/Scripts/activate
pip install pip -U
pip install -r requirements.txt
