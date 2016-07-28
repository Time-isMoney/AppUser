application.config.php
        Application
        ApplicationMod
        SncSocial 1st before 2th ZfcBase, 3th ZfcUser
        'ScnSocialAuth',
    [2] 'ScnSocialAuthMod',
        
        'ZfcBase',
        'ZfcBaseMod',//add myFunc
        #'Voodoo773Localization',
        
        'ZfcUser',
        'GoalioRememberMe',//ZfcUser +remember_me
        'GoalioMailService',
        'GoalioForgotPassword',//ZfcUser +forgot password
        'MtMail',
        'HtUserRegistration',//ZfcUser RG by Email
    [1] 'ZfcUserMod',//ZfcUser + ALL NEW VIEW
        'BjyAuthorize',
        #'BjyAuthorizeMod',
        
        #'UserProfile',
        #'UserProfileMod',

mail.config.global.php
  для регистрации нужно заполнить куда будет отправляться почта SMPT
  
запуск модулей
  'ScnSocialAuth',
  'ScnSocialAuthMod',
