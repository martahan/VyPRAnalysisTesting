# VyPRAnalysisTesting

Script for testing the VyPR analysis library.

In order to run the tests, clone this repository and clone VyPR, VyPRServer and VyPRAnalysis into this new repository. You will also need the verdicts database.

``git clone git@github.com:martahan/VyPRAnalysisTesting.git``

``cd VyPRAnalysisTesting``

``git clone git@github.com:martahan/VyPRServer.git``

``git clone git@github.com:martahan/VyPRAnalysis.git``

``git clone git@github.com:pyvypr/VyPR.git``

``cd VyPRServer``

``git clone git@github.com:pyvypr/VyPR.git``

``cd ..``

``cp verdicts.db VyPRServer/verdicts.db``

``rm verdicts.db``


Finally, run the test script as:

``python test_script.py``
