Working on copy of notebook 
- running into issues: ERROR: Could not find a version that satisfies the requirement torchaudio (from versions: none) & ERROR: No matching distribution found for torchaudio - on Block one 
- further issues with block 3: unable to run block 3: NameError                                 Traceback (most recent call last)
/tmp/ipykernel_10437/1483841409.py in <cell line: 0>()
 -   8 # 1. Run the prediction.
 -   9 # Because we didn't specify an engine, it runs locally on the T4 GPU via PaddlePaddle.
---> 10 results = pipeline.predict(input_data)
 -   11
 -   12   # 2. Iterate through the results (if you passed a directory, this loops through all images)

NameError: name 'pipeline' is not defined
- unable to run block 4 properly and unable to run block 5 
