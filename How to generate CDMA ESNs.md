#How to generate CDMA ESNs

#### CDMA ESNs
	
	set serveroutput on;
	begin
  		--CDMA
  		dbms_output.put_line ('ESN ST CDMA STSAR335C= ' || get_test_esn('STSAR335C') );
  		dbms_output.put_line ('ESN ST CDMA NTLGS220C= ' || get_test_esn('NTLGS220C') );
  		dbms_output.put_line ('ESN ST CDMA STSAM828C= ' || get_test_esn('STSAM828C') );
  	end;
 

###Back to [[Home]] page


