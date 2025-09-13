BACKEND:

Folders and Files not originally available in the beginning of our project development (backend):
- `backend/build`
- `backend/dist`
- `backend/app.spec`

Then the following command will be ran inside the `backend` folder: 
```shell
C:\Users\sabar\AppData\Local\Packages\PythonSoftwareFoundation.Python.3.11_qbz5n2kfra8p0\LocalCache\local-packages\Python311\Scripts\pyinstaller.exe --onefile --noconsole --add-data "best.pt;." app.py
```

-> This will create `backend/app.spec`, `backend/build`, `backend/dist`
-> Inside `backend/dist`, `app.exe` will be present

-----------------------------------------------------------------------------------------------------

FRONTEND:

Folders and Files not originally available in the beginning of our project development (frontend):
- `frontend/dist`
- `frontend/backend/app.exe`

The `app.exe` from the `backend/dist` will be copied and pasted inside `frontend/backend`

Then the following command will be ran inside the `frontend` folder: 
```shell
cd "C:\Users\sabar\Downloads\Gear Fault Detection (Dataset and Other Files)\gear_fault_app\frontend"
```
```shell
npm run dist
```

-> This will create `frontend/dist`
-> Inside `frontend/dist`, `Gear Fault App Setup 1.0.0` will be present, which will be our main `.exe` component