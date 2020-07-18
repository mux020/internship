Incase if the org throws an error for "return Database.getQueryLocator(query);" please use new or different org, as this happened to me and I had to create a new developer org.

To create records run apex file using "create_records.create_rec();" in Debug > Open Execute Anonymous Window./n
To execute batch file execute "batch_apex b =new batch_apex();" "Database.executeBatch(b);" in Anonymous Window.
To delete records execute "create_records.delete_rec();" in Anonymous Window.

