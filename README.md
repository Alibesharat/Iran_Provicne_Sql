# Iran_Provicne_Sql
کوئری استان های ایران برای مایگریشن دات نت
و اس کیو ال
    
  <b>For Migrations  :</b> 
  
  Step 1 - Add Migraiton:
    
          Add-Migration RunSqlScript_Add_Provinces

     

Step 2 - Modify Up Metohde Of Genreated Code :

        protected override void Up(MigrationBuilder migrationBuilder)
            {
               string Query= "INSERT INTO Proivnces(Name) VALUES('آذربایجان شرقی'), ('آذربایجان غربی'), ('اردبیل'), ('اصفهان'), ('البرز'), ('ایلام'), ('بوشهر'), ('تهران'), ('چهارمحال بختیاری'), ('خراسان جنوبی'), ('خراسان رضوی'), ('خراسان شمالی'), ('خوزستان'), ('زنجان'), ('سمنان'), ('سیستان و بلوچستان'), ('فارس'), ('قزوین'), ('قم'), ('کردستان'), ('کرمان'), ('کرمانشاه'), ('کهکیلویه و بویراحمد'), ('گلستان'), ('گیلان'), ('لرستان'), ('مازندران'), ('مرکزی'), ('هرمزگان'), ('همدان'), ('یزد')";

                migrationBuilder.Sql(Query);
            }
        
 Step 3 update database:
 
      update-database
      
