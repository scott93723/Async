# AsyncTask

   AsyncTask             UI thread
   
   
   
   在此方法可以做         toast , alertdialog
   onPrexcute()
   UI thread
   
   doInBackgroud()
   不可以做
   超級重要
   如果在裡面做
   toast 
   跟ALertDialog
   會崩潰
   
   
   
   可以做ui thread動作
   onPostExecute()
   
   
