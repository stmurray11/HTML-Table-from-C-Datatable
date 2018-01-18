# HTML-Table-from-C-Datatable
Convert C# datatable to stringbuilder containing HTML table

public static void html_table_from_dt(ref DataTable dt, ref System.Text.StringBuilder sb, string sTableId = "",
                                              int iPercentWidth = 0, string sTableClass = "table", bool bHeaderRow = true,
                                              List<int> iArrColWidths = null, int iTableWidth = 0, string sListOfColsToCenter = "")
    
Returns Value:
A stringbuilder object containing HTML table
 
Parameters:
ref DataTable dt              the populated datatable, by ref
ref StringBuilder sb          the stringbuilder, by ref,that the method will populate with the HTML table
string sTableId = ""          optional id for the table element
int iPercentWidth = 0,        optional int for table width as % of client window
string sTableClass = "table"  optional CSS style for the table
bool bHeaderRow = true        optional boolto inccludee header row with fieldnames or not
List<int> iArrColWidths       optional int array of individual column width (in px) for the HTML table
int iTableWidth = 0           optional width (in px) for the table
string sListOfColsToCenter    optional csv list of columns to align text to center
