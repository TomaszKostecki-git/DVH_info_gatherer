# DVH_info_gatherer
Get data and paramethers (like V95 in PTV) to one Excel file from multiple Monaco RT system generated DVH.csv files

Needed imports

import openpyxl
from openpyxl.utils.dataframe import dataframe_to_rows
import pyodbc
import pandas as pd
import os
from os.path import join
import pandas as pd

Notebook 'Sortowanie DVH...' filters DVH files, as they can com in different formats (cumulative or differential, absolute or relative, in cGy or Gy)
Notebook 'Otwieranie_CSV' parses the files, combines the data with the Mosaiq data base and creates an excel file.
