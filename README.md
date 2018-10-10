## Dev instructions
cd /Users/karan_sharma1/Desktop/CC_Website

source env/bin/activate

python main.py

check http://localhost:8080

## Push to GCP
gcloud app deploy

gcloud app browse

## Setup
cd /Users/karan_sharma1/Desktop/CC_Website

virtualenv env

source env/bin/activate

pip install  -r requirements.txt

python main.py

check http://localhost:8080
