# ai-store-analytics

This app uses Movidius NCS to analyze store cuztomers and inventories.  So we can have business insight such as store customer vs. revenue on hourly basis, as well as tracking inventory so that the workers doesnt have to track them manually.

# Demo Video
You can check out youtube to see how the app works.
https://www.youtube.com/watch?v=h1KcPffLOhQ

# What's needed to run the Demo
You will need a ubuntu machine along with Movidius NCS https://developer.movidius.com/start

# How to run the code
You will need to install the Movidius NCS as well as node.js, after that youc an run the following script to get the project running.

    # Clone the repo
    $ git clone https://github.com/Nyceane/ai-store-analytics.git
    $ cd ai-store-analytics/node_server
    $ node server.js
    
    # Run the server side
    $ cd ai-store-analytics/node_server
    $ node server.js
    
    # Run the people tracker
    $ cd ..
    $ cd python_ncs
    $ python3 people.py

    # Run the inventory tracker
    $ cd ..
    $ cd python_ncs
    $ python3 inventory.py



You can then use browser to go to http://localhost:8888 to see the demo
