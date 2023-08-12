# Developed and Deployed a Portfolio Web Application on AWS
# Development 
Developed the whole portfolio website using HTML,CSS and JS.
# Deployment
We will directly connect to the VM through the AWS platform
After connecting with the Instance, we will run the following commands on the console:
1. sudo su -
2. yum update -y
3. yum install -y httpd
4. systemctl status httpd
5. mkdir aws_assg3
6. cd aws_assg3
7. For this assignment we have created a portfolio website which we have uploaded on Github.com.
8. Copy the Download Link for the .zip file of the portfolio
9. using the wget command, download the zip file to the folder.
10. unzip the master.zip file and navigate in to the ShreyasKulkarni_Portfolio-master folder using the cd command.
11. move all the contents from the folder to “/var/www/html/”

**Edit the Inbound Rules**
check the status of httpd and then enable & start httpd using the following commands
  systemctl status httpd
  systemctl enable httpd
  systemctl start httpd
Now open the public ipv4 address allocated to the EC2 instance we created in new tab. We will be able to see the Portfolio Website.
We have Successfully Deployed the Web Application on AWS Cloud!

# Description
A portfolio website serves as a digital showcase of your work, skills, accomplishments, and personality. It's a versatile tool with various uses, particularly for individuals in creative, design, development, writing, photography, and other fields. Here are some key uses of a portfolio website:

1. **Showcasing Work:** The primary purpose of a portfolio website is to display your best work. Whether you're an artist, designer, writer, photographer, or any other creative professional, a portfolio allows you to present your projects, pieces, or creations to potential clients, employers, collaborators, and the public.

2. **Personal Branding:** A portfolio website helps you establish and promote your personal brand. It allows you to create a consistent and professional online presence that aligns with your expertise and style.

3. **Attracting Clients or Employers:** If you're a freelancer, consultant, or entrepreneur, a portfolio website can help you attract potential clients. Employers also often look for portfolios when hiring, as they provide tangible evidence of your skills and accomplishments.

4. **Networking:** A portfolio website can serve as a hub for your online networking efforts. It provides a platform to connect with peers, industry professionals, and potential collaborators. It can also facilitate discussions and opportunities through contact forms, social media links, and networking plugins.

5. **Demonstrating Expertise:** For professionals in technical fields like web development, software engineering, or data science, a portfolio website can demonstrate your skills through interactive projects, code samples, and case studies.

6. **Educational Purposes:** Teachers, educators, and trainers can use a portfolio website to share resources, course materials, and examples of student work. This can enhance their online teaching presence and credibility.

7. **Job Applications:** When applying for jobs or freelance gigs, you can provide a link to your portfolio website in your resume or cover letter. This allows potential employers to explore your work in more detail.

8. **Self-Expression:** A portfolio website is a space to express your artistic vision, creativity, and personality. You can use design elements, layout choices, and content to convey who you are as a professional and an individual.

9. **Continuous Improvement:** Maintaining a portfolio encourages you to regularly update your work and showcase your latest accomplishments. This process can help you track your progress, set new goals, and improve your skills over time.

10. **Marketing and Promotion:** A portfolio website can be integrated with social media platforms and other marketing efforts, helping you reach a wider audience and promote your work to potential clients, fans, and followers.

