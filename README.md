# django_quiz
a generic quiz system in Django

based on: https://github.com/tomwalker/django_quiz

features
----------------
* Question order randomisation
* Storing of quiz results under each user
* Previous quiz scores can be viewed on progress page
* Correct answers can be shown after each question or all at once at the end
* Logged in users can return to an incomplete quiz to finish it
* The quiz can be limited to one attempt per user
* Explanation for each question result can be given
* Multiple choice question type
* True/False question type
* Essay question type
* Display an image alongside the question
* After selecting a larger pool of questions, a quiz can be set to show a random subset rather than all within the pool
* Start and end times for sitting exams are recorded
* i18n support

Heroku deployment
-----------------
$heroku create <app_name>

$git push heroku master

after the push, the app can be access via <app_name>.herokuapp.com

