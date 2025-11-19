# Website-project-phcloudaws
I built this simple static website and hosted it on AWS S3 to get hands-on experience with cloud deployment and S3 static website hosting.
## Steps I Took

1. **Created an S3 bucket and enabled static website hosting**  
   ![Step 1 - Bucket creation](images/step1-bucket.png)

2. **Uploaded the website files**  
   - Made sure `index.html` and other main files were in the root of the bucket  
   ![Step 2 - Upload files](images/step2-upload.png)

3. **Configured public access**  
   ![Step 3 - Permissions](images/step3-permissions.png)

4. **Tested the website in a browser**  
   - Initially it didn’t work because I uploaded the whole folder instead of just the files  
   - Moving the files to the root fixed it  
   ![Step 4 - Website view](images/step4-website.png)