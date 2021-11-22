

//////////////////////////////   Create Virtual Environment  /////////////////////

python -m venv work_env

mkdir flask

cd flask


create python file in your working space(flask)

create a workspace going in View>>command pallet>> Open Workspace setting in vs code and then click setting .json

and write
{

    "python.pythonPath": "Path/{your path}/python"
    
}


Note Error: Running scripts disabled

https://tecadmin.net/powershell-running-scripts-is-disabled-system/

Kill the current terminal and you are ready to go.

if not redirected Do:

 & D:/UPwork/PythonOpenCvproject/hosting/work_env/Scripts/activate.ps1
 & {path of script of env folder}/activateps1



//////////////////////////   Extract The requirements ////////////////////////

pip freeze > requirements.txt


///////////////////////////     App redirect        /////////////////////

Create a Procfile

web: gunicorn app:app     #Give the Path

pip install gunicorn

