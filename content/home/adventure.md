+++
# An example of using the custom widget to create your own homepage section.
# To create more sections, duplicate this file and edit the values below as desired.

date = "2016-04-20T00:00:00"
draft = false

title = "Highlights"
subtitle = ""
widget = "custom"

# Order that this section will appear in.
weight = 3

+++
<ul class="timeline ">
    <li>
      <div class="timeline-badge" style="background-color: #EC7063"><i class="fa fa-server" aria-hidden="true"></i></div>
      <div class="timeline-panel" id="web_dev">
        <div class="timeline-heading" style="background-color: #EC7063">
          <h4 class="timeline-title">Web developer
            <p><small class="text-muted"><i class="glyphicon glyphicon-time"></i>&nbsp;Spring '16 - Present</small></p>
          </h4>
        </div>
        <div class="timeline-body">
          <p>Web application developer at Iowa State University</p>
        </div>
      </div>
    </li>
    <li class="timeline-inverted">
      <div class="timeline-badge success"><i class="fa fa-trophy" aria-hidden="true"></i></div>
      <div class="timeline-panel" id="honor">
        <div class="timeline-heading" style="background-color: #52BE80">
          <h4 class="timeline-title">Deans List Honor
            <p><small class="text-muted"><i class="glyphicon glyphicon-time"></i>&nbsp;Fall '16</small></p>
          </h4>
        </div>
        <div class="timeline-body">
          <p>Deans List Honor at Iowa State University</p>
        </div>
      </div>
    </li>
    <li>
      <div class="timeline-badge info"><i class="fa fa-user-o" aria-hidden="true"></i></div>
      <div class="timeline-panel"  id="leader">
        <div class="timeline-heading">
          <h4 class="timeline-title">Project Leader
            <p><small class="text-muted"><i class="glyphicon glyphicon-time"></i>&nbsp;Fall '16 - Spring '17</small></p>
          </h4>
        </div>
        <div class="timeline-body">
          <p>Design and implement software application for client.</p>
        </div>
      </div>
    </li>
    <li class="timeline-inverted">
        <div class="timeline-badge warning"><i class="fa fa-university" aria-hidden="true"></i></div>
      <div class="timeline-panel" id="college">
        <div class="timeline-heading" style="background-color: #F5B041">
          <h4 class="timeline-title">Computer Engineering
            <p><small class="text-muted"><i class="glyphicon glyphicon-time"></i>&nbsp;Fall '13 - Present</small></p>
          </h4>
        </div>
        <div class="timeline-body">
          <p>Begin adventure at Iowa State University.</p>
        </div>
      </div>
    </li>
</ul>

<script>
$(document).ready(function(){
    $(window).scroll(function() {
        if($( "#web_dev" ).isInViewport().length > 0){
            $( "#web_dev" ).addClass( "animated fadeInLeft" );
        }
        if($( "#honor" ).isInViewport().length > 0){
            $( "#honor" ).addClass( "animated fadeInRight" );
        }
        if($( "#leader" ).isInViewport().length > 0){
            $( "#leader" ).addClass( "animated fadeInLeft" );
        }
        if($( "#college" ).isInViewport().length > 0){
            $( "#college" ).addClass( "animated fadeInRight" );
        }
    });
});
</script>