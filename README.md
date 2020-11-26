# RstudioServer_on_Colab
This repository builds a Rstudio-server on Google colaboratory.

# prerequisite
[ngrok](https://ngrok.com/)  token is required.

# How to launch Rstudio-server on Google Colab?
1. Open Rstudio_server.ipynb on Colab
2. Run all codes one by one. You need the ngrok API token. 
3. The "rstudio" is created. The password should be defined by user.
4. Launch the ngrok produced weblink. Rstudio-server will be launched.

# Note
The rstudio server does not accept the root user.  
To access google drive, the "googledrive" package should be installed.  


# References
- https://towardsdatascience.com/colab-free-gpu-ssh-visual-studio-code-server-36fe1d3c5243
- https://memo.chezo.uno/Google-Colaboratory-VS-Code-code-server-3b0f4ae8181c49ecac0c99f6e4017133
