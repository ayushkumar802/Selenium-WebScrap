# Selenium-WebScrap
This project demonstrates how I used Selenium in Python to scrape structured educational content from the Gyan Board learning platform for 9th Standard students. The goal was to extract all chapters, topic names, and their respective content into a clean, readable format.

🔍 Project Overview
Gyan Board hosts subject-wise educational material structured by Chapters and Topics. The content was dynamically loaded and required advanced navigation techniques to scrape accurately.

In this project, I:

Scraped complete page content from the platform using Selenium.

Extracted Chapter and Topic names from the navigation bar using XPath and the following-sibling:: axis.

Built a clean pandas DataFrame with Chapter, Topic, and Content columns.

Exported the final structured content to a .csv file.

Documented the full scraping workflow in a Jupyter Notebook.
