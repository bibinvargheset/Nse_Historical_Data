# Nse_Historical_Data
1 Min Historical data for Nifty 500 Stocks.
Contains data from 2018.
The files are in **.parquet** format.

Includes 1 min data for Nifty, BankNifty, FinNifty and MidcapNifty indexes.

They can be read using Pandas as shown below.

  **df = pandas.read_parquet(<filename.parquet>)**

Requires:
    pandas 
    parquet 
    pyarrow

Can be installed using pip.