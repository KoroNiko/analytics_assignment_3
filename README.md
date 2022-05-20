# analytics_assignment_3

If you want to run the notebooks from your local IDE you have to do the following:

From your IDE (I'm using Visual Studio Code so the procedure is about this IDE):

1) Open a terminal instance and run the python script 'local_proxy.py' 
2) Open another terminal instance and run the batch file 'letsgo-win.bat' 
    - This will launch the Jupyter Server. It is important to have this file running
3) Open one of the notebooks, and in the bottom right, choose to connect to a remote Jupyter server
4) Insert the URL that was generated durin step 2. You can find it in the terminal output. Should be localhost with a long token
5) Once you're connected to the remote server, go to the top right option to choose your kernel.
6) From the list of the available kernels, some remote kernels should be available to you as well (I have 2 remote kernels. One for my 
    virtual environment and one for my native Python installation). Choose the kernel that you want (REMOTE).
7) It should work now. Try running one of the notebooks up until before the .stop() method of the stream. If everything went well you 
    should be able to see some data.