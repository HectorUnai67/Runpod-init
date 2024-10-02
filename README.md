# Johnsons Runpod Templates
<br />
Making use of Runpod easier and less painful for some, maybe.<br />
<br />
ComfyUI WIP (stable): [https://runpod.io/console/deploy?template=25hd4rhmj7&ref=0czffee4]<br />
KohyaSS WIP (stable): [https://runpod.io/console/deploy?template=gdu4jus5ud&ref=0czffee4]<br />
OneTrainer WIP (stable): [https://runpod.io/console/deploy?template=c150zcigz7&ref=0czffee4]<br />
<br /><br />

## Acknowledgements

 - [Docker Author: AI-Dock](https://github.com/ai-dock)
 - [The Project we are using](https://github.com/ai-dock/comfyui)
 - [Template built on this Release](https://github.com/ai-dock/comfyui/pkgs/container/comfyui/279832227?tag=latest-cuda)


## Deployment

To deploy this project run our template in Runpod, you can search for it with "DJZ" and find it in the list. Assign a GPU & your Netowrk Storage, then start it up. Some pods take a long time to install everything, this is normal, so keep an eye on the logs.

enter these credentials when you go to launch the web interface.<br />
```
  user = user, password = password
```
<br /><br />
# DJZ-init (ComfyUI) <br />
<br /><br />
I will provide initialisation scripts if needed for various tasks in this repo. <br />
![image](https://github.com/user-attachments/assets/d2aa2164-e651-4bc9-9f22-d1723b20acb7) <br />
place the link to the startup script in the indicated field <br />
<br /><br />
Environment Variables > Provisioning Script <br />
[https://github.com/MushroomFleet/Runpod-init/blob/main/DJZ-init/default.sh](https://github.com/MushroomFleet/Runpod-init/blob/main/DJZ-init/default.sh) <br />
Above is the first work in progress script, which adds Flux Dev support, my Flux Lora's, the DJZ-Nodes pack & some custom nodes required to run my workflows. <br />
Workflows should also be added when this project is finished. Use the Raw link in the env var's:
```https://raw.githubusercontent.com/MushroomFleet/Runpod-init/refs/heads/main/DJZ-init/default.sh```
<br /><br />
## 🔗 Links
[![portfolio](https://img.shields.io/badge/my_portfolio-000?style=for-the-badge&logo=ko-fi&logoColor=white)](https://fivebelowfive.uk/)
[![twitter](https://img.shields.io/badge/twitter-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white)](https://twitter.com/mushroomfleet)
