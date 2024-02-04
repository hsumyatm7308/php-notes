# => echo
  echo ဆိုတာက parameter တွေရဲ့  output data ကို document or browser ပေါ် ပြသပေးနိုင်တဲ့ language construct လို့ ဆိုရပါမယ်။ strings, variables တွေကို comma နဲ့ ခွဲပြီး   (သို့မဟုတ်)  အတူတူ တွဲပြီးလည်း သုံးနိုင်တဲ့ multi output ထုတ် ပေးနိုင်တဲ့ကောင်ဖြစ်ပါတယ်။

### - Single string 

      `<?php

         echo "Hello";
         // output -   Hello 

       ?>`
### - Multi strings 

      `<?php

         echo "Aung Aung", "Maung Maung"; 
         // output -  Aung AungMaung Maung 

       ?>`

  echo မှာ parenthesis ထည့်ချင်လည်းရသလို မထည့်လည်းရပါတယ်။ သို့သော် ကွာခြားချက်တော့ ရှိပါတယ်။ 

### - Single parameter 

     `<?php
        echo ("Aung Aung");   // output -  Aung Aung  
     ?>`

### - Multi parameter

      `<?php
         echo ("Aung Aung", "Maung Maung");   // output -  error 
       `?>

  ဆိုလိုချင်တာက parenthesis ထည့်တဲ့အခါ multi parameter မရပါဘူး။ 




# =>print() 

   echo နဲ့ အလားတူ language construct တစ်ခုဖြစ်တဲ့ print လည်း ရှိပါသေးတယ်။ print မှာတော့ parenthesis ထည့်သည်ဖြစ်စေ ၊ မထည့်သည်ဖြစ်စေ parameter တစ်ခုပဲ လက်ခံပါတယ်။ 

 ### - Single parameter 

      `<?php

           print "Mingalarpar";
           // output -   Mingalarpar 

            print ("Mingalarpar");
           // output -   Mingalarpar 

       ?>`


### - Multi parameter 

       ` <?php

           print "Aung Aung", "Maung Maung"; 
           // output -  error  

           print ("Aung Aung", "Maung Maung"); 
           // output -  error 

        ?>`

