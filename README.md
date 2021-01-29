Npm packages which you need:
    -npm i axios
    -npm i vue
    -npm i vue2-google-maps
    -npm i vue-router
    -npm i vue-loader

Add to env file:
    THEME=maps
    GOOGLE_MAPS_API_KEY=AIzaSyBjR-olNjXwUPM5WcuZYCgcOBxF61sNByU
   
Run this for authentificate:
    composer require laravel/jetstream
    php artisan jetstream:install livewire
    
Add this code to 'store' method in vendor\laravel\fortify\src\http\controllers\RegisteredUserController:

    DB::table('role_user')->insert([
            'user_id' => $user->id,
            'role_id' => 2
     ]);
     
Also you need to type in console:
    php artisan migrate
    php artisan db:seed
    
In the end, you need to type in console 'npm run dev'
