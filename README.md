AWS Project: Host a website on amazon S3

Step 1: Create a Bucket in Amazon S3
-Create Bucket
-Select region(Cape Town)
-Bucket name(kitsosenwedi-project)
-Object Ownership(ACLs enbled)
-Bucket owner preferred
-Clear - Block all public access
-Bucket versioning - enable
-Create bucket
SCREENSHOT
![Bucket](https://github.com/user-attachments/assets/7f0f885e-9c69-4e8a-9856-740991fc3247)

Step 2: Upload website content to your bucket
-Choose your bucket(kitsosenwedi-project)
-Upload files 
-Add files
-Upload
SCREENSHOT
![upload](https://github.com/user-attachments/assets/4bbc7329-1ca2-4939-be39-e446ccbcb57a)

-Objects
SCREENSHOT
![objects](https://github.com/user-attachments/assets/3e5bce19-b8ee-4a91-ba91-ea735776090a)


Step 3: Configure a static website on amazon S3
-Buckets
-Properties tab
-Scroll to static hosting(Edit)
-Enable
-Host a static website
-Type index.html
-Save changes
-Click url link
SCREENSHOT
![Error](https://github.com/user-attachments/assets/3aa45ede-3b6a-4357-a780-fc93bf5280ce)

-Select objects(index.html and assets folder)
-Actions: Make public ACL
![Make-Public](https://github.com/user-attachments/assets/8f1a0442-eeb2-4fc0-9813-dcff0f1818b0)
