All files have been cleaned, analyzed and have corresponding visuals.
CRM+sales, Flight INFO and Lego sets fiiles have additional Data Dictionaries and Executiver summary reports.


An example of the Data Documentation/Dictionary - Flight INFO

STEPS	      COLUMN/VARIABLE	           ACTION TAKEN/FORMULA	          WHY/BUSIINESS LOGIC

1	          Flight details	            TEXTSPLIT         	      To split data into suitable columns
2	          Flight details	           Removed column	              It was no longer needed
3	          To/From	                    TEXTSPLIT                To split location to TO and FROM
4	          Price	          Multiply 1 with paste special        To remove formatting and converted to currency	
5	          Date	                mid/Text to columns	              To format as a date type
6	        Flow card?	                      IF	                  To change the values from 1/0 format to Yes/No
7	      Created a Quarter column	    "Q"&ROUNDUP	                To breakdown the year into quarters
