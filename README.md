Docker Basic ToDo app
---------------------

This application is configured in multi container environment. It's running two containers linked via network, one is running the app and the other the MYSQL.

Getting Started
---------------

Please open your browser to 5.180.182.140:3000 and start using the app.

Development
-----------

This project has a docker-compose.yml file, which will start the mkdocs application on the above remote machine and help you see changes instantly.

This application was deployed on the remote machine by creating SSH keys and using "ansible-playbook -i inventory.yaml playbook_ToDo_ALL.yml" which files are attached in the repository. 

As an improvement it should be modified the usage from root to some other user.

Contributing
------------

If you find typos or other issues with the tutorial, feel free to create a PR and suggest fixes!

If you have ideas on how to make the tutorial better or want to suggest adding new content, please open an issue first before working on your idea. 
