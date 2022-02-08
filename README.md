# CakePHP
Download file: cleancodevietnam.com/cleancode.zip
Config local:
- database: Edit file
` app/config/database.php `
` admin/config/database.php `
- Url: Edit file
` app/config/bootstrap.php `
` admin/config/bootstrap.php `
define('DOMAINAD','http://'.$_SERVER["HTTP_HOST"].'/admin/') => define('DOMAINAD','http://'.$_SERVER["HTTP_HOST"].'cleancode/admin/');
define('DOMAIN','http://'.$_SERVER["HTTP_HOST"].'/') => define('DOMAINAD','http://'.$_SERVER["HTTP_HOST"].'cleancode/');
- database file `database/database.sql`
