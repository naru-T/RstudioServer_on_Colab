# RstudioServer_on_Colab
This repository builds a Rstudio-server on Google colaboratory.

# prerequisite
[ngrok](https://ngrok.com/)  token is required.

# How to launch vscode-server on Google Colab?
1. Open Rstudio_server.ipynb on Colab
2. Run all codes one by one. You need the ngrok API token. Some other actions such as google account authorization are required.
3. Launch the ngrok produced weblink. vscode-server will be launched.

# Note
At this moment, as the rstudio server does not accept the root user, it is difficult to access google drive data.

# References
- https://towardsdatascience.com/colab-free-gpu-ssh-visual-studio-code-server-36fe1d3c5243
- https://memo.chezo.uno/Google-Colaboratory-VS-Code-code-server-3b0f4ae8181c49ecac0c99f6e4017133
