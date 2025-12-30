Project parameters

Goal: Create a notebook that generates a printable file that aligns with the dimensions of Avery 5395 labels. Final files can be PDF or PNG

Data Input: CSV with First Name, Last Name, Job Title, Company, and a list of 5 hobbies


Useful functionality: 
* Ideally, we want to define a box where the name should be centered, and the code can select the largest font size that allows the name to fit within that box.
* Same process for Job Title and Company (combined in one line as "Title @ Company") 
* Each hobby should be represented by an icon, which is stored in assets/icons/
* First, create an image file for each individual name tag (2.33 x 3.375)
* For a full sheet of labels, assemble 8 name tags onto one sheet, matching the edges of the label stickers (8.5 x 11) 
