
cd C:\A_uwPython\SP_Online_PY230\lesson8\csrf-example\csrf_example\grader
rmvirtualenv csrfexample
mkvirtualenv csrfexample
edit requirements.txt use the following instead:
	MarkupSafe==1.1.1
pip install -r requirements.txt
python setup.py
start python main.py


