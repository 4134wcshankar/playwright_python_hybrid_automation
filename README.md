# playwright_python_hybrid_automation
playwright hybrid automation









To Eexceute Tests on Mac:
- Move to Project directory
  - (venv_hybrid_playwright) bash-3.2$ cd  /Users/{YourUserName}/python_test_env/playwright_python_hybrid_pom
- To Run Tests Generate Allure reports on Mac
  - Install:
    - (venv_hybrid_playwright) bash-3.2$ brew install allure
    - (venv_hybrid_playwright) bash-3.2$ pip install allure-python-commons
  - Generate reports:
    - (venv_hybrid_playwright) bash-3.2$ pytest ./test_cases/car_model_test.py  --alluredir=allure-results
    - (venv_hybrid_playwright) bash-3.2$ allure serve allure-results  
