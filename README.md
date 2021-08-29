

//////////////////////////////   Create Virtual Environment  /////////////////////

python -m venv work_env

mkdir flask

cd flask


create python file in your working space(flask)

create a workspace going in command pallet in vs code and then click setting .json

and write
{

    "python.pythonPath": "Path/.......your path......../python"
    
}


Note Error: Running scripts disabled

https://tecadmin.net/powershell-running-scripts-is-disabled-system/

Kill the current terminal and you are ready to go.



//////////////////////////   Extract The requirements ////////////////////////

pip freeze > requirements.txt


///////////////////////////     App redirect        /////////////////////

Create a Procfile

web: gunicorn app:app     #Give the Path

pip install gunicorn

