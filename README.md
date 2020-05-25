## ML-Model-Flask-Deployment
This is my Template for deploying machine learning models. The machine learning algorithm is simple multiple regression.

### Structure
1. model.py 
2. app.py 
3. request.py 
4. templates

### Running the project
1. Ensure that you are in the project home directory. Create the machine learning model by running below command -
```
python model.py
```
This would create a serialized version of our model into a file model.pkl

2. Run app.py using below command to start Flask API
```
python app.py
```
By default, flask will run on port 5000.

3. Navigate to URL http://localhost:5000

Enter valid numerical values in all 3 input boxes and hit Predict.

If everything goes well, you should  be able to see the predcited salary vaule on the HTML page! 

![alt text](http://www.thepythonblog.com/wp-content/uploads/2019/02/Result.png)

