I always forgetting destination of Devise routes. Hopes it will help me in future :)

```
         new_user_session GET    /users/sign_in(.:format)            users/sessions#new              Login page (6.0)
             user_session POST   /users/sign_in(.:format)            users/sessions#create           Login action (6.1)
     destroy_user_session DELETE /users/sign_out(.:format)           users/sessions#destroy          Logout action (6.2)
        new_user_password GET    /users/password/new(.:format)       users/passwords#new             Password restoration form (1.0)
       edit_user_password GET    /users/password/edit(.:format)      users/passwords#edit            Entering new password form (1.2)
            user_password PATCH  /users/password(.:format)           users/passwords#update          Saving new password (1.3)
                          PUT    /users/password(.:format)           users/passwords#update          -
                          POST   /users/password(.:format)           users/passwords#create          Password restoration request action (1.1)
 cancel_user_registration GET    /users/cancel(.:format)             users/registrations#cancel      Expire session data (7.0)
    new_user_registration GET    /users/sign_up(.:format)            users/registrations#new         Registration form (3.0)
   edit_user_registration GET    /users/edit(.:format)               users/registrations#edit        Form changing password, email (2.0)
        user_registration PATCH  /users(.:format)                    users/registrations#update      Saving profile (2.1)
                          PUT    /users(.:format)                    users/registrations#update      -
                          DELETE /users(.:format)                    users/registrations#destroy     Removing user action (4.0)
                          POST   /users(.:format)                    users/registrations#create      Saving registration action (3.1)
    new_user_confirmation GET    /users/confirmation/new(.:format)   users/confirmations#new         Confirmation email form (5.0)
        user_confirmation GET    /users/confirmation(.:format)       users/confirmations#show        Confirmation action (5.2)
                          POST   /users/confirmation(.:format)       users/confirmations#create      Confirmation requesting action (5.1)
          new_user_unlock GET    /users/unlock/new(.:format)         users/unlocks#new               Unlock form (8.0)
              user_unlock GET    /users/unlock(.:format)             users/unlocks#show              Unlocks user (8.2)
                          POST   /users/unlock(.:format)             users/unlocks#create            Sends unlock email (8.1)
```