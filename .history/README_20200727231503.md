# VScode_on_Colab_for_geospatial
This repository builds a vscode-server on Google colaboratory with additional settings for R geospatial analyses 

# prerequisite
[ngrok](https://ngrok.com/)  token is required.

# How to launch vscode-server on Google Colab?
1. Open VScode_server.ipynb on Colab
2. Run all codes one by one. You need the ngrok API token. Some other actions such as google account authorization are required.
3. Launch the ngrok produced weblink. vscode-server will be launched.
4. If you would like to use R on VScode, run testRcode.R .libPaths() is a key to store all packages installation on google drive. It means you can save and load them everytime you launched your vscode-server. It will save your time to prepare the analysis environment.

# References
- https://towardsdatascience.com/colab-free-gpu-ssh-visual-studio-code-server-36fe1d3c5243
- https://memo.chezo.uno/Google-Colaboratory-VS-Code-code-server-3b0f4ae8181c49ecac0c99f6e4017133
