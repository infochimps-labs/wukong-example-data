
Download Retrosheet database: http://www.baseballheatmaps.com/retrosheet-database-download/

echo CREATE DATABASE retrosheet |  mysql -u root ; cat compressed/retrosheet.sql | mysql -u root retrosheet
for foo in 20*_retrosheet.sql ; do echo "  === $foo" ; echo CREATE DATABASE `basename $foo .sql` |  mysql -u root ; cat $foo | mysql -u root `basename $foo .sql` ; done
for foo in 19*}s_retrosheet.sql ; do echo "  === $foo" ; echo cat $foo mysql -u root ; done


Recipients of Retrosheet data are free to make any desired use of the information, including (but not limited to) selling it, giving it away, or producing a commercial product based upon the data. Retrosheet has one requirement for any such transfer of data or product development, which is that the following statement must appear prominently:

     The information used here was obtained free of
     charge from and is copyrighted by Retrosheet.  Interested
     parties may contact Retrosheet at "www.retrosheet.org".

You can copy this statement and paste it into your document or click here to display the text of the statement. Then you can save it to a file using the "Save As..." command under the file menu in your browser.
Retrosheet makes no guarantees of accuracy for the information that is supplied. Much effort is expended to make our website as correct as possible, but Retrosheet shall not be held responsible for any consequences arising from the use of the material presented here. All information is subject to corrections as additional data are received. We are grateful to anyone who discovers discrepancies and we appreciate learning of the details.
