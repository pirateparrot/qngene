How to execute the scripts in "Export_gen_files"
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


[![Stories in Ready](https://badge.waffle.io/bigdatafoundation/qngene.png?label=ready&title=Ready)](https://waffle.io/bigdatafoundation/qngene)
# qngene

[![Join the chat at https://gitter.im/bigdatafoundation/qngene](https://badges.gitter.im/bigdatafoundation/qngene.svg)](https://gitter.im/bigdatafoundation/qngene?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)
Genetic Scalable Analytical Query Engine

Contact GitHub API Training Shop Blog About
© 2016 GitHub, Inc. Terms Privacy Security Status Help
