# Grocery_List
#### Created a python script that is capable of scanning a reciept and return only relevant product item from the list. This script uses microst vision API and uses optical character recongnition to scan the prodcuct items. It filtes the noise in two stages, it fisrt checks the corpus of the supermarket (toy corpus) for the relevant items and finally removes the quantity items (any numeric no in the list) from it and creates a list from it and only keep the unique items from the list. 
So any noise like supermarket name, date and codes are removed from it. 
