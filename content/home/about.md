+++
# About/Biography widget.

date = "2016-04-20T00:00:00"
draft = false

widget = "about"

# Order that this section will appear in.
weight = 1


# List your qualifications (such as academic degrees).
[[education.courses]]
  course = "B.Sc. in Computer Engineering"
  institution = "Iowa State University"
  year = 2017

# List your academic interests.
[interests]
  interests = [
  "Big Data",
  "Cloud Computing",
  "Mobile and IoT Applications",
  ]
 
+++

<div id="biography">
    <h1>Biography</h1>
    <p>
        I am a Computer Engineering student at Iowa State University graduating in Spring of 2017. Experienced in back-end web development in LAMP environment with a demonstrated history of working in the higher education industry. Comfortable with all parts of software life cycle including architecture design, implementation and support. Strong engineering professional with a Bachelor’s Degree focused in Computer Engineering from Iowa State University.
    </p>
</div>

<script>
$(document).ready(function(){
    if($( "#biography" ).isInViewport().length > 0){
        $( "#biography" ).addClass( "animated fadeInUp" );
    }
    if($( "#interests" ).isInViewport().length > 0){
        $( "#interests" ).addClass( "animated fadeInUp" );
    }
    if($( "#grad" ).isInViewport().length > 0){
        $( "#grad" ).addClass( "animated fadeInUp" );
    }
});
</script>
