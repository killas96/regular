# regular expression
'full_name' => "/(^[а-яА-ЯёЁ\-]{3,100})([ ]{1,1})([а-яА-ЯёЁ\-]{3,55})?([ ]{0,1})?([а-яА-ЯёЁ\-]{3,100})$/u", // Иванов Иван, Иванов иван Иванович  
'phone_user' => "/^7\([0-9]{3}\)[0-9]{3}-[0-9]{4}$/", //phone  
'phone_user' => "/^7[0-9]{10}$/",  //phone  
'inn_user' => "/^[0-9]{12}$/", //integer  
'promo_code' => "/^[a-zA-z0-9]{9}$/", //code  
'hospital_code'=> "/^([0-9]+)$/", //integer  
'policy'=> "/^1$/", //check  
