cd /home/z/my-project

# إضافة remote
git remote add origin https://github.com/YOUR_USERNAME/raed-neom.git

# رفع الكود
git push -u origin master
Name: raed-neom-backend
Region: Oregon (US West)
Branch: main
Root Directory: download/raed-backend
Runtime: Python 3
Build Command: pip install -r requirements.txt
Start Command: uvicorn main:app --host 0.0.0.0 --port $PORT
Instance Type: Free
