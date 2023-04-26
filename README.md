# URL Generator

## Introduction
I created this simple python script to automate the process of generating URLs for a list of words that I was studying while preparing for the GRE using a wordlist by GregMAT. I found it helpful to look up example sentences for new words that I came across in order to better understand their usage.

## How it Works
The code reads input from a CSV file named `file_name.csv`, which contains a list of words. For each word, the script generates a URL that takes the user directly to an example sentence using the word in context. The generated URLs are then exported to an Excel file. By opening all the links simultaneously, it saves time and effort compared to typing the URLs explicitly for 900 words in the list.

## Customization
If you want to generate URLs for a different website, simply open the `URL_Generator.ipynb` file and change the variable `url` which is sitting in the for loop, with the URL of your choice.

I hope this tool can help you study more efficiently. Feel free to suggest any improvements or contribute to the project. 
