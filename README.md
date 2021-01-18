# Iran_Provicne_Sql
کوئری استان های ایران برای مایگریشن دات نت
و اس کیو ال
    
  <b>For Migrations  :</b> 
  
  Step 1 - Add Migraiton:
    
          Add-Migration RunSqlScript_Add_Provinces

     

Step 2 - Modify Up Metohde Of Genreated Code :

        protected override void Up(MigrationBuilder migrationBuilder)
            {
               string Query="INSERT INTO Proivnces(Name) VALUES(N'آذربایجان شرقی'), (N'آذربایجان غربی'), (N'اردبیل'), (N'اصفهان'), (N'البرز'), (N'ایلام'), (N'بوشهر'), (N'تهران'), (N'چهارمحال بختیاری'), (N'خراسان جنوبی'), (N'خراسان رضوی'), (N'خراسان شمالی'), (N'خوزستان'), (N'زنجان'), (N'سمنان'), (N'سیستان و بلوچستان'), (N'فارس'), (N'قزوین'), (N'قم'), (N'کردستان'), (N'کرمان'), (N'کرمانشاه'), (N'کهکیلویه و بویراحمد'), (N'گلستان'), (N'گیلان'), (N'لرستان'), (N'مازندران'), (N'مرکزی'), (N'هرمزگان'), (N'همدان'), (N'یزد')";
            migrationBuilder.Sql(Query);
            }
        
 Step 3 update database:
 
      update-database
      
