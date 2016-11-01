How to execute the scripts

-----------------------
gentotsv.py
-----------------------
python gentotsv.py -> (it takes the default sourcedir, destinationdir and sample file from config.py)

or

gentotsv.py  -h<help> -t<threads> -s<sourcedir> -d<destinationdir> -f<samplefile> -> (all the parameters are optionals)

------------------------
export.py
------------------------
python export.py {destination_des_tsv} {ip_postgresql_server} {schema_postgresql} {owner_schema_postresql} {password_owner_schema}{import_genotypes_flag}

Ex:
python export.py "/Test/output" 127.0.0.1 advancedb prognomix pass12345 Y
