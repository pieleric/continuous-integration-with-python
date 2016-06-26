# continuous-integration

### introduction to CI with Travis   
https://www.youtube.com/watch?v=buXwBr9H3VY  

### introduction to pytest
https://www.youtube.com/watch?v=LdVJj65ikRY 

### what to find on this repo
CI with Travis and pytest.    
inpired by these 7 volumes:   
automated tests with pytest   
https://ilovesymposia.com/2014/10/01/continuous-integration-0-automated-tests-with-pytest/  

Measuring test coverage  
https://ilovesymposia.com/2014/10/02/continuous-integration-1-test-coverage/  

Setting up test configuration files  
https://ilovesymposia.com/2014/10/13/continuous-integration-in-python-3-set-up-your-test-configuration-files/  

travis CI  
https://ilovesymposia.com/2014/10/15/continuous-integration-in-python-4-set-up-travis-ci/  

### requirements
to test python code locally, install pytest and the plugin cov:  
sudo pip install pytest  
sudo pip install pytest-cov   
to test with Travis CI, you need a Travis CI and github accounts.      

###usage for this repo  
git clone https://github.com/ksator/continuous-integration.git  
cd continuous-integration/ 

### local tests  
py.test  
py.test --cov maths.py  
py.test --cov-report term-missing --cov=maths.py  
py.test --cov-report term-missing  
py.test --cov-report term-missing --ignore maths2.py  








