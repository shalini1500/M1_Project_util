# High Level Test Plan
* 	  Description	             ,            Input	           ,   	         Actual Output
* 01   Check patient                          123 (aadhar no)	               not found
* 02	Check patient registration status	     100 (aadhar no)	                 (found)
* 03	Check patient vaccination status	      89 (patient id)	               (vaccinated)


# Low Level Test Plan
* Test ID	Description	                ,       Input	      ,      Expected output 	 ,      Actual Output
* 01	Check patient reg  status	        125 (aadhar no)	            0	                0 (registered, not vaccinated)
* 02	Check patient reg status	        130 (aadhar no)	            1	                 1 (registered, vaccinated)
* 03	Check patient vaccination  status	9 (patient id)	            3                           1 (first dose)
* 04	Check patient vaccination status	89 (patient id)	            2	                        2 (second dose)
* 05	Check patient vaccination status	2 (patient id)	          3                    3 (already vaccinated)
