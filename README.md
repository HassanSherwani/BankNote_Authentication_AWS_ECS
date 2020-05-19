# BankNote_Authentication_AWS_ECS
Implementation of an end-end ML project and deployment using aws

# For testing API using postman

query : ttp://127.0.0.1:5000/predict?variance=2&skewness=3&curtosis=2&entropy=1 <br>
result : Either 0 for non-authentic and 1 for authentic banknote

# Modules

pip3 install -r requirements.txt <br>

(pandas, Flask,request, sklearn , numpy,pickle)

# Results

### Output from query

!["User Interface"](images/img1.png)


### Output from loaded test file

!["User Interface"](images/img2.png)

# For front end testing using swagger

Use this command:<br> 
http://127.0.0.1:5000/apidocs/


# Results

### For GET Method

!["User Interface"](images/img3.png)

!["User Interface"](images/img4.png)

!["User Interface"](images/img5.png)

### For POST method

!["User Interface"](images/img6.png)

!["User Interface"](images/img7.png)
