# WearSignDataset

Repository for dataset of WearSign

## How to get dataset

As github is not suitable for sharing data, we uploaded the dataset to Dropbox. The link is: https://www.dropbox.com/s/phv83750hp8b7tm/cut_sentence.zip?dl=0

## Files in this repository

1. sign_word.csv: The order of the words in this file represents its class No. The class No of any word is its line No minus 1. For example `who` is the 4th word so a sample file named with class No of 3 represents it's a sample of `who`.

1. sign_order.csv: The order of the sentences in this file represents its class No. The class No of any sentence is its line No minus 1. For example `afternoon weather what` is the 28th sentence so a sample file named with class No of 27 represents it's a sample of `afternoon weather what`.

1. spoken_order.csv: Every sentence in this file is the corresponding sentence in `sign_order.csv`.