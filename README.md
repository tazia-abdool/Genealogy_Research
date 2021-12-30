# Genealogy_Research
The goal is to scrape old land ownership documents  (PDF, JPEG) from a public online source, apply text recognition and perform exploratory analysis &amp; data mining to create a usable, searchable database for the purpose of Genealogical Research.


Data Source  : http://190.213.4.242/scandocs

Task 1: The data exists inside directories and folders with an inconsistent naming schema. Data must be scraped from this source.
  Challenges:
    - Data must be scraped in such a way that it does not stress the source server
    - Data volume is unknown
   
   
Task 2: Once PDF & Jpeg files are retreived, text recognition must be applied to make the data mine-able
  Challenges:
    - Some documents may be low quality, faded, low resolution
    - Text is largely in flowery handwriting 
    
Task 3: Once text is associated with each document, perform exploratory analysis to determine how to make something useful out of the data
  Preliminary Ideas:
    -Clustering analysis - to see which documents are associated with each other . ( e.g multiple documents that track the owenership of a parcel of land)
    -A searchable database by name / location to retreive associated documents.
