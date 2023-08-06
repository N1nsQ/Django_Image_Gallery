# Django Image Gallery

This project was my fist full stack application and it is developed in collaboration with two other students. (See credits below.) Image gallery uses [SQLite](https://www.sqlite.org/index.html) as a database and it is created with [Django ORM](https://opensource.com/article/17/11/django-orm). Web site is styled using [Bootstrap](https://getbootstrap.com/).  

See the file [tietokannat_kuva-albumisovelluksessa.pdf](https://github.com/nina20126/Django_Image_Gallery/blob/main/tietokannat_kuva-albumisovelluksessa.pdf) for detailed documentation (in Finnish language only.)

### Features

* Create a user profile
* Add albums
  * Albums can be set private or public
  * Images can be re-ordered by dragging
* Add photos
  * to users own private albums
  * to users own public albums
  * to any public albums
* Delete albums which user has added
* Delete photos which user has added
* Add tags to photos
  * Tag page shows photos with the same tag in random order
* Photos and albums have titles, description, and date details
* Detail view of an album shows its photos
  * Photos can be ordered in ascending or descending order
  * Photos can be ordered by dragging the image
* The homepage shows all users public albums and users own private albums

### CREDITS
**Team members: [Mir4H](https://github.com/Mir4H) & [Hansikas](https://github.com/hansikas)**  
<br>
Tutorials used in this project:  
[Try Django 3.2 - Python Web Development Tutorial Series](https://www.youtube.com/playlist?list=PLEsfXFp6DpzRMby_cSoWTFw8zaMdTEXgL),  
[Django Photo Sharing App](https://github.com/hansikas),  
[Django Documentation](https://docs.djangoproject.com/en/3.2/topics/auth/default/),  
[PhotoSwipe](https://photoswipe.com/),  
[Deploying to Azure](https://www.youtube.com/watch?v=D6Wyk9q2JM0)
