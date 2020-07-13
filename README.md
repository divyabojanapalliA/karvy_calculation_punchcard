# karvy_calculation_punchcard
Documentation of karvy calculations punch card
Punch Card:
  Column names of Punchcard:
    Columns which a punchcard should contain are SNo, Columns, TableName, Mandatory, Must be and atleast one set of Source, Rule and replicate table name.
    SNo:
      Serial number is a unique identifier which indexes the rows in the excel.
    Columns:
      Required column names of particular tables.
    TableName:
      Name of table which the column belongs to.
    Mandatory:
      It is filled with either 'Y' or 'N' which tells its a mandatory column or not. If its 'Y' we will check whether the column contains some data if any row contains empty string or NULL value, those will get filterd out.
  
