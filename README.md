# Brooks

**[View Project](https://janettwalker.github.io/brooks/)**
----
# Train Scheduler

This project was a test for a position as a frontend web developer at BHC. The idea was to create a simple landing page for 

## Screenshots
Images of the train schedule and how users can add trains to the schedule.

![Cross Platform View](http://i1044.photobucket.com/albums/b447/janetwalker271989/BHC-cross-platform_zps4ddc6jzy.png "Cross platform view of the landing page.")


## Technologies
A brief listing of the technologies learned and applied.
- HTML5
- css
- jQuery
- Bootstrap


## Walk throughs of code
The click event that triggers downloadable material.

```
jQuery(document).ready(function($) {
   $('a[href$=".pdf"]')
        .attr('download', './assets/download/todownload.pdf')
        .attr('target', '_blank'); 
});
```

## Author

* **Janet Walker** - *Initial work* - [Janet Walker](https://github.com/janettwalker)


## Acknowledgments

* Huge shout out to all of the open source documentation out there!
