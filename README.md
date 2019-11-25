
MAIL_DRIVER=smtp

MAIL_HOST=smtp.mailtrap.io

MAIL_PORT=2525

MAIL_USERNAME=5f75236e6546c0

MAIL_PASSWORD=1e32ac7ccdcf6f

MAIL_ENCRYPTION=TLS

your mail.php on config you declare host as smtp.mailgun.org and port is 587 while on env is different. 

you need to change your mail.php to

'host' => env('MAIL_HOST', 'mailtrap.io'),

'port' => env('MAIL_PORT', 2525),

if you desire to use mailtrap.Then run

php artisan config:cache

or

https://myaccount.google.com/lesssecureapps

hitonit_example@gmail.com
