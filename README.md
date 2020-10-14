# laravel-slug-generator
Simple single file laravel unique slug generator.

## SETUP
copy file Sluggify.php to App\CustomClasses\

## USAGE 
to access from any Controller or Model, add the following at the top

```use App\CustomClasses\Sluggify.php```

to generate slug 

```$slug = Sluggify::slug('text','App\Model');```


