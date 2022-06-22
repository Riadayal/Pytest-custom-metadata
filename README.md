# How to add custom metadata to automation tests in Pytest on [LambdaTest](https://www.lambdatest.com/?utm_source=github&utm_medium=repo&utm_campaign=Pytest-custom-metadata)

If you want to add custom metadata to automation tests in Pytest on LambdaTest, you can follow the steps below. You can refer to sample test repo [here](https://github.com/LambdaTest/pytest-selenium-sample).

# Steps
With LambdaTest, you can add custom meta data to automation tests. These are added for tests by setting the data in `customData` capability. The code below illustrates the usage:

```
capabilities = {
        "build": "Sample PY Build",
        "platformName": "Windows 11",
        "browserName": "Chrome",
        "browserVersion": "latest",
		"customData": [ 	
						{ "_id": "5f46aaa69adf77cfe2bb4fd6", 
						"index": "0", 
						"guid": "9451b204-12f0-4177-8fe9-fb019b3e4bf3", 
						"isActive": "False", 
						"picture": "http//placehold.it/32x32" } ]
}
```

## Run your test

```bash
cd tests //navigate to tests directory
python sample_todo.py
```

# Links:

[LambdaTest Community](http://community.lambdatest.com/)

