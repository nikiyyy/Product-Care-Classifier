Problem:
I work as a data ingestion developer. Part of my job is to scrape web data and label it. The date we scrape comes from clothing products from online stores. Two of the product fields that we scrape are product description and care. Often, data for these to separate fields needs to be extracted from the same text element. Generally we split section that contains the care and decription by "." and then classify each sentance using keywords and regex. Using this method we generally achive 77% accuracy. it can be increased more by tiloring the method for the specific webcrawler but this takes time.

Description - text describing the product and cosmetic text used to sell the product

Care - instructions on how to wash the product and what its made of.

Solution:
By using naive bayes i was able to achive areound 93% accuracy.

Alternative solutions:
in the scraps folder i've left a few other solutions that yielded a lower result, but are still intresting solutions