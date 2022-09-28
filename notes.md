where this is from: https://github.com/app-generator/api-server-flask
 
 - name: Lint with flake8
      run: |
        # stop the build if there are Python syntax errors or undefined names
        flake8 . --count --select=E9,F63,F7,F82 --show-source --statistics
        # exit-zero treats all errors as warnings. The GitHub editor is 127 chars wide
        flake8 . --count --exit-zero --max-complexity=10 --max-line-length=127 --statistics
        

https://towardsdatascience.com/github-automated-testing-python-fdfe5aec9446

https://medium.com/swlh/automate-python-testing-with-github-actions-7926b5d8a865


seems like a good one: https://www.honeybadger.io/blog/django-test-github-actions/


some automated external ci cd testing framework: 
https://medium.com/snowflake/snowflake-ci-cd-with-github-actions-c2168ceb33bc



https://stackoverflow.com/questions/41569206/flask-sqlalchemy-foreign-key-relationships



Aggregation and composition example: 
https://medium.com/@dineshmadhup_75545/implementation-of-inheritance-composition-and-aggregation-in-python-aee2761cb2d0