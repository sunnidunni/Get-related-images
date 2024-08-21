# Get-related-images

Colab link: 

https://colab.research.google.com/drive/1pS8rC-I69E0f87ujUMoFTL8wIBVmaw8B#scrollTo=rTLXBWPLTAPh&uniqifier=3

Basically, this project uses the MNLI model to do a relation hypothesis test. It gets the probability that the caption is true given the text as the premise.

Steps:

1. Scrape entire website

2. Filter and get the main article + images
   
3. Chunk the main article into smaller portions for faster run time.

4. Generate and store captions for all images

5. Use NLP to compare captions to each portion, and return a confidence score of whether the caption is related to the text

6. Refurn images with ahigh confidence score
