# McCafe-Locations
This script takes all McDonald's locations, with id, from a json file on [pastebin](https://pastebin.com/E3NQVdQL).
Mcdonald's restaurants with McCafe are written in [this](https://www.mcdonalds.it/sites/default/files/legal/collezione_mccafe-2020-ristoranti_aderenti-v02.pdf) PDF file. I converted it in csv with tabula-py (source pdf file and target csv file are in this repository).
For every McCafe location written in csv, a nested for search its id from json and write it in a new json file.
