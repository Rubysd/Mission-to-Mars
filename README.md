# Mission to Mars

# Overview of Project

Robin's web app is looking good and functioning well, but she wants to add more polish to it. She had been admiring images of Mars’s hemispheres online and realized that the site is scraping-friendly. She would like to adjust the current web app to include all four of the hemisphere images. To do this, you’ll use BeautifulSoup and Splinter to scrape full-resolution images of Mars’s hemispheres and the titles of those images, store the scraped data on a Mongo database, use a web application to display the data, and alter the design of the web app to accommodate these images.

Deliverable 1: Scrape Full-Resolution Mars Hemisphere Images and Titles

Deliverable 2: Update the Web App with Mars Hemisphere Images and Titles

Deliverable 3: Add Bootstrap 3 Components

Extra: A written report on the employee database analysis README.md.

# Resources and Before Start Notes:

Data Source: Mission_to_Mars.ipynb, app.py, scraping.py and index.html

Data Tools: Jupyter Notebook, Python and MongoDB

Software: MongoDB, Python 3.8.3, Visual Studio Code 1.50.0, Flask Version 1.0.2

# Deliverable 1: Scrape Full-Resolution Mars Hemisphere Images and Titles
## Deliverable Requirements:
Using BeautifulSoup and Splinter, you’ll scrape full-resolution images of Mars’s hemispheres and the titles of those images.

Make a copy of your Mission_to_Mars.ipynb file, and rename it Mission_to_Mars_Challenge.ipynb.

Download the Mission_to_Mars_Challenge_starter_code.ipynb, copy the starter code, and paste at the end of your Mission_to_Mars_Challenge.ipynb file.

In Step 1, use your browser to visit the Mars Hemispheres website to view the hemisphere images.

Use the DevTools to inspect the page for the proper elements to scrape. You will need to retrieve the full-resolution image for each of Mars's hemispheres.

Results with detail analysis:
Make a copy of your Mission_to_Mars.ipynb file, and rename it Mission_to_Mars_Challenge.ipynb.

![Captura de pantalla (731)](https://user-images.githubusercontent.com/86340630/136678227-c35c57ae-eacd-45f9-b206-05af9876f935.png)
![Captura de pantalla (733)](https://user-images.githubusercontent.com/86340630/136678240-a2a281b6-1573-48df-824f-2e60a410ca3b.png)
![Captura de pantalla (735)](https://user-images.githubusercontent.com/86340630/136678357-6d17e036-62af-49b3-a948-b29f009a42df.png)

Download the Mission_to_Mars_Challenge_starter_code.ipynb, copy the starter code, and paste at the end of your Mission_to_Mars_Challenge.ipynb file.

![Captura de pantalla (737)](https://user-images.githubusercontent.com/86340630/136678522-9ebb01da-6234-4379-bc72-9c765c92cc11.png)
![Captura de pantalla (739)](https://user-images.githubusercontent.com/86340630/136679348-a8087666-6648-4e75-9461-81430974a33d.png)

In Step 1, use your browser to visit the Mars Hemispheres website to view the hemisphere images.

![Captura de pantalla (743)](https://user-images.githubusercontent.com/86340630/136709536-da24f014-5a9b-412d-957c-3371d51dac25.png)
![Captura de pantalla (745)](https://user-images.githubusercontent.com/86340630/136709593-6703f89d-8810-4248-83d6-55259fdc9ccb.png)

Use the DevTools to inspect the page for the proper elements to scrape. You will need to retrieve the full-resolution image for each of Mars's hemispheres

![Captura de pantalla (747)](https://user-images.githubusercontent.com/86340630/136709690-05125d78-3aee-42a0-a74a-1b254d773de5.png)
![Captura de pantalla (749)](https://user-images.githubusercontent.com/86340630/136709733-c6c64549-4d58-49f3-887c-7cdb0dc9e417.png)
![Captura de pantalla (754)](https://user-images.githubusercontent.com/86340630/136709827-07547c2d-b88d-456b-9a92-33707f81e731.png)
![Captura de pantalla (755)](https://user-images.githubusercontent.com/86340630/136709853-db04f436-cf9f-4620-a4af-72b488293a0d.png)
![Captura de pantalla (756)](https://user-images.githubusercontent.com/86340630/136709878-188cbf49-1b0d-41fb-b0c2-db43f87a4a40.png)
![Captura de pantalla (757)](https://user-images.githubusercontent.com/86340630/136709893-8b23d1c9-ed35-4d97-9196-bfd3d7c137ac.png)

# Deliverable 2: Update the Web App with Mars’s Hemisphere Images and Titles

## Deliverable Requirements:

Using your Python and HTML skills, you’ll add the code you created in Deliverable 1 to your scraping.py file, update your Mongo database, and modify your index.html file so the webpage contains all the information you collected in this module as well as the full-resolution image and title for each hemisphere image

The scraping.py file contains code that retrieves the full-resolution image URL and title for each hemisphere image.

The Mongo database is updated to contain the full-resolution image URL and title for each hemisphere image.

The index.html file contains code that will display the full-resolution image URL and title for each hemisphere image.

After the scraping has been completed, the web app contains all the information from this module and the full-resolution images and titles for the four hemisphere images.

Results with detail analysis:

The scraping.py file contains code that retrieves the full-resolution image URL and title for each hemisphere image.

![Captura de pantalla (772)](https://user-images.githubusercontent.com/86340630/136710567-e9c8c3b9-bf43-4a26-b3b1-970fed54b40f.png)
![Captura de pantalla (773)](https://user-images.githubusercontent.com/86340630/136710577-e62fbbb8-6028-4b6d-abbb-19d12580ae60.png)
![Captura de pantalla (774)](https://user-images.githubusercontent.com/86340630/136710494-484a4ede-bc6b-404f-9c65-2097a824ed2b.png)
![Captura de pantalla (775)](https://user-images.githubusercontent.com/86340630/136710515-569bd66a-a4e5-4445-90b0-d04795dcf2e6.png)

The Mongo database is updated to contain the full-resolution image URL and title for each hemisphere image.

![Captura de pantalla (777)](https://user-images.githubusercontent.com/86340630/136710666-53aba9da-81b7-4540-b5f0-6c7505dc10d7.png)

The index.html file contains code that will display the full-resolution image URL and title for each hemisphere image

![Captura de pantalla (782)](https://user-images.githubusercontent.com/86340630/136710774-35615632-7f81-4c6d-a7b8-0e554e9fd29f.png)
![Captura de pantalla (783)](https://user-images.githubusercontent.com/86340630/136710789-06e5e98a-8a23-4b47-a87a-71228a398ba4.png)
![Captura de pantalla (784)](https://user-images.githubusercontent.com/86340630/136710854-9e4e3035-b73c-483c-9844-5205db4a58af.png)
![image](https://user-images.githubusercontent.com/86340630/136710840-7aeafbe2-3cbb-4ea3-8e8f-f9db3abd7523.png)

# Deliverable 3: Add Bootstrap 3 Components
## Deliverable Requirements:
For this part of the Challenge, update your web app to make it mobile-responsive, and add two additional Bootstrap 3 components to make it stand out.

The webpage is mobile-responsive.
Two additional Bootstrap 3 components are used to style the webpage.
Results with detail analysis:
The webpage is mobile-responsive.

# Webpage - View

![image](https://user-images.githubusercontent.com/86340630/136712192-a5e2d31c-f6b7-4707-90ae-0c0707f9ce0f.png)

# Galaxy S5 - Mobile View

![Captura de pantalla (796)](https://user-images.githubusercontent.com/86340630/136712266-a5a62415-3db2-4ee2-9285-88c92bd7a3e9.png)

# iPad Pro - Tablet View

![Captura de pantalla (795)](https://user-images.githubusercontent.com/86340630/136712291-09dced92-bbf8-4332-b48f-b0675eec7fdc.png)

Two additional Bootstrap 3 components are used to style the webpage.

![Captura de pantalla (800)](https://user-images.githubusercontent.com/86340630/136712421-011bc073-add3-491b-b99e-af80b0533a09.png)
![Captura de pantalla (798)](https://user-images.githubusercontent.com/86340630/136712439-93d52b29-f747-45c2-bbf4-8d1408ffa415.png)










