
1. Extract the zip file.
2. Login into AWS Educate Account and open EMR and S3 bucket.
3. Open new jupyter notebook and start cluster to run this notebook.  
4. Copy Spam Classification code into  jupyter notebook and clear kernel and run all cells.
5. You can run data processing using input files - business.json and reviews.json.
5.S3 bucket link to the Output of data preprocessing and input to the spam classification
	(we stored the dataset into a csv format from json format after all the preprocessing and used this in the further part, Thus we are providing the link of csv file obtained after 			data_preprocessing this data file becomes the input to spam classification (our main algorithm))
 	Input for data preprocessing - 
	business.json: https://jsonfileyelp.s3.amazonaws.com/yelp_academic_dataset_business.json (Object URL)	 
	reviews.json: https://jsonfileyelp.s3.amazonaws.com/yelp_academic_dataset_review.json (Object URL)


Input Files - 
-------------------
S3 bucket link to the Input file: https://reviwssannilbhav.s3.amazonaws.com/reviews1.csv (Object URL)


Output File - 
-------------------
S3 bucket link to the final output
k_vs_silhuotte_score : https://reviwssannilbhav.s3.amazonaws.com/output_final/s_diatance_new/finaloutput_K_vs_s_score.csv
Final Output : https://reviwssannilbhav.s3.amazonaws.com/output_final.zip