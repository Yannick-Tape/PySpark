# PySpark




# Copier-coller l'archive .tar de ma VM vers mon PC windows  
scp -i "C:\Users\33669\Downloads\data_enginering_machine.pem" ubuntu@3.249.240.218:~/Docker/exam_TAPE.tar .


# Pour relancer le notebook on doit d'abord charger le var d'environnement 
source ~/.bashrc
jupyter notebook --ip=0.0.0.0 --port=8888 --no-browser --NotebookApp.token='' --NotebookApp.password=''
http://54.155.214.216:8888      (54.155.214.216 est l'adresse IP de ma VM)


######################## transfère le fichier gps_app.csv de ton PC vers ta VM via scp dans le fichier PySpark #########################
# Ouvre Git Bash sur ton PC Windows (si tu n’as pas, installe-le : Git Bash download)
# Va dans ton dossier où est ton fichier .pem :
cd /c/Users/33669/Downloads
# Lance la commande
scp -i data_enginering_machine.pem /c/Users/33669/Downloads/gps_app.csv ubuntu@54.155.214.216:/home/ubuntu/PySpark

json_bracket.json
scp -i data_enginering_machine.pem /c/Users/33669/Downloads/json_bracket.json ubuntu@54.155.214.216:/home/ubuntu/PySpark






