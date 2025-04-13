playwright_python_hybrid_automation


Step 1:
    - Create a virtual env
        - python3 -m venv venv_playwright_python_hybrid
    - Install all requirements for 
        -  pip3 install -r requirements.txt 
    - Install playwright
        - pip install pytest-playwright
        - playwright install
    - Install allure
        - brew install allure
        - pip install allure-python-commons
        - pip install allure-pytest
        


To Eexceute Tests On Mac:

Move to Project directory

To Run Tests, Generate reports and view html reports:s
- Project Dir: 
    - (venv_hybrid_playwright) bash-3.2$ cd /Users/{YourUserName}/python_test_env/playwright_python_hybrid_pom
- Run Tests and generate report:
    - (venv_hybrid_playwright) bash-3.2$ pytest ./test_cases/car_model_test.py --alluredir=./reports/allure_results
- View Reports:
    - (venv_hybrid_playwright) bash-3.2$ allure serve ./reports/allure_results
