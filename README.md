# win2022-codespaces
# Note
Only supports 4 core github codespaces, 16GB RAM, 32GB Storage. change github codespaces in settings
![note](https://github.com/user-attachments/assets/9c8f9249-e041-4ec1-bace-41ad38cadb40)

If you use 2 core it will be very laggy

# usage :

sudo su

apt update

pip install docker

git clone https://github.com/diana-lis/win2022-codespaces.git

cd win2022-codespaces

unzip win2022.zip

python3 main.py

![Capture](https://github.com/user-attachments/assets/71a2eae0-1697-4a7f-8a56-73aa22246479)

![Capture2](https://github.com/user-attachments/assets/715ff377-9a9a-4bf9-b2cd-1e094cabf348)

# Wait a moment for the Windows file download process to complete
![Capture3](https://github.com/user-attachments/assets/1515451d-9d42-451d-90cd-73e8983cc23c)
# reload the web browser
![Capture4](https://github.com/user-attachments/assets/9a9c83de-7909-4db7-a69c-9a4342d9af20)
# Wait a moment for the installation process automatically
![Capture5](https://github.com/user-attachments/assets/4e7034de-6186-41bf-800e-9f4e92caf3fb)
# Enjoy!
![Capture6](https://github.com/user-attachments/assets/6124d70e-4530-4fee-88dd-21ff521dec5e)
If you want to connect it to RDP you can use a service like ngrok with the command: ngrok tcp 3389. or other services that support tcp forwarding. But keep in mind that Free Ngrok Service only has a Data Transfer Out bandwidth of 1 GB, so if the quota is exceeded, RDP will automatically be disconnected.
# RDP USERNAME AND PASSWORD
Name : Mpragans

Password : 123456

# Note
just for your information, if you stop codespaces which has Windows installed and then want to reopen it and type "python3 main.py" it won't work
![unnamed](https://github.com/user-attachments/assets/e661f385-02e2-4714-ba66-348910b4858f)
use the command: "docker start windows" to restart Windows
