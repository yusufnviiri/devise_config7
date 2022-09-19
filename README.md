# README

## initail set up

# After rails devise:install command
# Copy contents of the config/initializers/devise.rb
# Copy contents turbo_devise_controller.rb in app/controllers

# add  devise_scope :user do
    # Redirests signing out users back to sign-in
    get "users", to: "devise/sessions#new"
  end
#  in the routes.rb file
enjoy
