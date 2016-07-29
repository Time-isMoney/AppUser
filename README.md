application.config.php
//1
        Application
        ApplicationMod

//2
        'ScnSocialAuth',
        'ScnSocialAuthMod',
//3        
        'ZfcBase',
        'ZfcBaseMod',
        #'Voodoo773Localization',

//4        
        'ZfcUser',
        'GoalioRememberMe',//ZfcUser +remember_me
        'GoalioMailService',
        'GoalioForgotPassword',//ZfcUser +forgot password
        'MtMail',
        'HtUserRegistration',//ZfcUser RG by Email
//5 все изменения и слушатели
        'ZfcUserMod',
//6        
        'BjyAuthorize',
        'BjyAuthorizeMod',
//7
        #'UserProfile',
        #'UserProfileMod',

db.global.php
  база + zfcuser_zend_db_adapter (ZfcUser)
  
mail.config.global.php
  для регистрации нужно заполнить куда будет отправляться почта SMPT
 
scn-social-auth.global.php
  ключи и настройка в Dev соц сети и доступы в FB
