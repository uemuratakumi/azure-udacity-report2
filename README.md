# azure-udacity-report2
In this report, I explain the whole of Azure-ML.

## whole of azure-ml
This is whole of Azure ML Service.
![udacity_report](https://github.com/uemuratakumi/azure-udacity-report2/assets/132246132/d3b3d774-c87c-43c5-8faa-e4007432b689)

In the project, we can make model by using auto-ML, Pipeline, and python script on Jupyter Notebook.

Any method, we can deploy the model as endpoint(WebAPI).

And we can use the endpoint by sending API key and data to endpoint URL.

In real project, model should update at fixed interval.

The Pipeline support the update automatically.

## key step of how to use Azure-ML
I explain the key step of how to use Azure-ML.

### make data set
We can easity upload file from local PC to Ature-ML.
This is a sample of upload data.

![dataset](https://github.com/uemuratakumi/azure-udacity-report2/assets/132246132/da3b97fb-cf5b-4062-936f-d6df3379ab3e)

### conduct the experiment
By using upload data, we can conduct the experiment.

If experiment is done fine, "Completed" is shown like below.

![exp-complete](https://github.com/uemuratakumi/azure-udacity-report2/assets/132246132/07da2541-1235-4a5a-9d4e-c4bd7693d9da)

### check the lerned model
If experiment is done fine, learned model is created like below.

![best_model](https://github.com/uemuratakumi/azure-udacity-report2/assets/132246132/c7ab2e1f-3985-4b91-885c-8793dbd5f369)

### model deploy and operation check
After created model, we can deploy the model as endpoint.

This is the sample of deploy model that is application insights enables is true.

![applicationinsights](https://github.com/uemuratakumi/azure-udacity-report2/assets/132246132/77502339-3fe1-4bc1-a91b-37d0acc8d2fe)

And this is the screenshot of running result of logs.py.

![logspy](https://github.com/uemuratakumi/azure-udacity-report2/assets/132246132/95ffb07a-d85b-4148-a6f9-ba85c0d1a93c)

And swagger is useful about operation check.

This is the sample of swagger operations.

![awagger01](https://github.com/uemuratakumi/azure-udacity-report2/assets/132246132/b75c92a4-3bf1-415e-98e4-20a750dbaa17)

![swagger02](https://github.com/uemuratakumi/azure-udacity-report2/assets/132246132/c17361e0-6b3f-43fa-a52d-7cff962299b6)

![swagger03](https://github.com/uemuratakumi/azure-udacity-report2/assets/132246132/508fd7a0-f072-42b6-b880-2e8ce0e1ca9e)


