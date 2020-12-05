#### The creation Day

This API will use Marshmallow for data serialisation.(Not `json` because I donot want hackers like [@adnanhasan251](https://github.com/adnanhasan251) )to do a malicious SQL injection in the database.
I honestly donot have any idea about creating an API so I will mostly be following tutorials across the web but will also try to add somethings of my own.

- The basic idea:
   1. Well I donot have any special use case for Mlon Eusk which cannot be catered by pre existing APIs in the market. However I just want to keep this API as a skeleton for my future projects.


#### 5 December 2020

Just crossed my mind that the API should be made asynchronous for making it useful in real life scenarios. Multithreading was an option but since the tasks of the API is not that cpu extensive, I backed away from it. Nevertheless, Async funcs should do the job for me currently. Also found a third party module to handle the asynchronous tasks called [Celery](https://pypi.org/project/Flask-Celery/)
Some more links :
1. https://docs.celeryproject.org/en/latest/getting-started/first-steps-with-celery.html
2. https://flask.palletsprojects.com/en/1.1.x/patterns/celery/



