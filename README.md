### exTrade


#### install
```bash
git clone https://github.com/satbit/extrade.git
cd extrade
pyvenv-3.6 ~/.extrade
source ~/.extrade/bin/activate
pip install -r requirements.txt
export SECRET_KEY='<mysecretkey>'
python manage.py migrate
python manage.py createsuperuser --email EMAIL
```

