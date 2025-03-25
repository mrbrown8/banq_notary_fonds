# banq_notary_fonds
databasing fonds of Public Notaries housed at BAnQ

https://sqlite.org/index.html
https://banq.qc.ca/
https://openseadragon.github.io

insert autoincrement in lines: perl -pe 's/^/++$i/ge' html.txt 
csv import into sqlite: https://stackoverflow.com/questions/1045910/how-to-import-load-a-sql-or-csv-file-into-sqlite
