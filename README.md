# Data Scraper for Daftarsekolah.net

During my tenure as a Data Analyst and Market Intern at Kelas Pintar, I was assigned a project to develop an automated data collection method from a public education directory — daftarsekolah.net. This website provides comprehensive listings of educational institutions across Indonesia, categorized by region, level, and type.

The primary objective of this task was to extract and compile structured data on schools under the supervision of the Ministry of Religious Affairs (KEMENAG), such as Madrasah Ibtidaiyah (MI), Madrasah Tsanawiyah (MTs), and Madrasah Aliyah (MA). These datasets were intended to support the company’s market research efforts by mapping the distribution and potential of schools in specific regions (provinces, cities, and districts).

To achieve this, I designed and implemented a Python-based web scraping workflow using Google Colab. The scraping process utilized libraries such as Requests and BeautifulSoup to fetch HTML content and parse relevant information, including school names, locations, accreditation statuses, and contact details. I also configured automated pagination detection to ensure the scraper could navigate multiple pages without manual intervention.

The data scraping solution proved to be significantly more efficient than manual data collection. While traditional copy-paste methods could take up to half a day to gather information from hundreds of pages, the automated script completed the same task in approximately 30 minutes to 3 hours, depending on data volume. This efficiency improvement enabled the marketing and business development teams to access updated and reliable school data on demand, reducing human error and freeing up valuable work time.

Overall, this project not only enhanced data accessibility and accuracy but also demonstrated how data automation can accelerate business processes and improve decision-making. It was a valuable learning experience in combining data engineering techniques with practical business applications, strengthening my ability to deliver data-driven solutions in a real-world context.
