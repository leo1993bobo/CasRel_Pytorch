NYT raw data is downloaded from https://drive.google.com/open?id=10f24s9gM7NdyO3z5OqQxJgYud4NnCJg3, containing train.json, test.json, and valid.json 

Run generate.py to convert the numerical mentions into string mentions. Move the converted files to NYT/

Also, the test data should be split by overlapping types, i.e., Normal, SEO, and EPO. Move the split files to NYT/test_split_by_type/
