# Initial setup in venv
    cd /d D:\...\dir_project
    python -m venv venv
    venv\Scripts\activate
    pip3 install -r requirements.txt


# Create python from interface ui
    pyuic6 interface_ui/calc_variant_2.ui -o main.py

# Run
    D:\...\dir_project\venv\Scripts\python.exe D:\...\dir_project\main.py

# or
    cd /d D:\...\dir_project
    venv\Scripts\python.exe main.py
