# TableReader

Integrated 2D table manager<br>
- Encapsulates file handling process, leaving only pandas dataframes
- Takes CSV file, Excel file or a folder of CSV files
- Built in property manager

Usage:
``` Python
from lib_TableReader import TableReader
tableReader = TableReader('filename.csv')
tableReader.methodCall()
```
