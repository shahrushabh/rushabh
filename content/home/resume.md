+++
# An example of using the custom widget to create your own homepage section.
# To create more sections, duplicate this file and edit the values below as desired.

date = "2016-04-20T00:00:00"
draft = false

title = "Resume"
subtitle = ""
widget = "custom"

# Order that this section will appear in.
weight = 3

+++
<ul class="timeline ">
    <li>
      <div class="timeline-badge" style="background-color: #CD6155"><i class="glyphicon glyphicon-check"></i></div>
      <div class="timeline-panel">
        <div class="timeline-heading" style="background-color: #CD6155">
          <h4 class="timeline-title">Web developer
            <p><small class="text-muted"><i class="glyphicon glyphicon-time"></i>&nbsp;Summer 2015 -</small></p>
          </h4>
        </div>
        <div class="timeline-body">
          <p>Backend web developer at Iowa State University</p>
        </div>
      </div>
    </li>
    <li class="timeline-inverted">
      <div class="timeline-badge success"><i class="glyphicon glyphicon-star"></i></div>
      <div class="timeline-panel">
        <div class="timeline-heading" style="background-color:green">
          <h4 class="timeline-title">Deans List Iowa State University</h4>
        </div>
        <div class="timeline-body">
          <p>Deans List Honor</p>
        </div>
      </div>
    </li>
    <li>
      <div class="timeline-badge danger"><i class="glyphicon glyphicon-credit-card"></i></div>
      <div class="timeline-panel">
        <div class="timeline-heading">
          <h4 class="timeline-title">Project Leader</h4>
        </div>
        <div class="timeline-body">
          <p>Design, Implement and manage solution for client.</p>
        </div>
      </div>
    </li>
    <li class="timeline-inverted">
        <div class="timeline-badge warning"><i class="glyphicon glyphicon-education"></i></div>
      <div class="timeline-panel">
        <div class="timeline-heading" style="background-color: #F5B041">
          <h4 class="timeline-title">Computer Engineering</h4>
        </div>
        <div class="timeline-body">
          <p>Started attending college at Iowa State University.</p>
        </div>
      </div>
    </li>
    <li>
      <div class="timeline-badge info"><i class="glyphicon glyphicon-floppy-disk"></i></div>
      <div class="timeline-panel">
        <div class="timeline-heading">
          <h4 class="timeline-title">Hadoop Projects</h4>
        </div>
        <div class="timeline-body">
          <p>Hadoop projects.</p>
          <hr>
          <div class="btn-group">
            <button type="button" class="btn btn-primary btn-sm dropdown-toggle" data-toggle="dropdown">
              <i class="glyphicon glyphicon-cog"></i> <span class="caret"></span>
            </button>
            <ul class="dropdown-menu" role="menu">
              <li><a href="#">Action</a></li>
              <li><a href="#">Another action</a></li>
              <li><a href="#">Something else here</a></li>
              <li class="divider"></li>
              <li><a href="#">Separated link</a></li>
            </ul>
          </div>
        </div>
      </div>
    </li>
</ul>