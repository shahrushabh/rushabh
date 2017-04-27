+++
title = "Resume"
date = "2017-01-01T00:00:00Z"
math = false
highlight = false
widget = "custom"

# Optional featured image (relative to `static/img/` folder).
[header]
image = ""
caption = ""
+++
<style>
    h1{
        color: #074a6a;
        text-transform: uppercase;
        margin-top: 100px;
    }
</style>
<br/>
<button id="toggle" type="button" class="btn" style="float:right;background:transparent;border-color:#074a6a;color:#074a6a;">EXPAND ALL</button><br/>
<style>
.panel-primary, .list-group-item-heading, .small{
    color: #5D6D7E;
}
</style>
<div id="resume">
<div class="panel panel-primary">
  <div href="#summary" data-toggle="collapse" style="background-color: #37838F" class="panel-heading">Summary</div>
  <div class="panel-body collapse" id="summary">
  <p class="left-space">Experienced Software Developer with a demonstrated history of working in the higher education industry. Skilled in web technologies (LAMP Stack, Java, and Python), Big data processing (Hadoop Eco System) and exposed to embedded programming. Strong engineering professional with a Bachelor’s Degree focused in Computer Engineering from Iowa State University. </p>
  </div>
</div>

<div class="panel panel-primary">
  <div href="#professional_experience" data-toggle="collapse" style="background-color: #37838F" class="panel-heading">Experience</div>
  <div class="panel-body collapse" id="professional_experience">
      <h4 class="list-group-item-heading"> Backend Developer <span class="small">@</span><a href="http://admissions.iastate.edu" target="_blank" class="small">Office of Admissions</a>, <a href="http://iastate.edu" target="_blank" class="small">Iowa State University</a> 
      <small><i style="float:right">May '16 - May '17</i></small>
      </h4>
      <p class="list-group-item-text">
      <ul style="list-style-type:circle;">
          <li> Develop web applications on LAMP stack in an agile environment. </li>
          <li> Implement PHP scripts that performs batch jobs for data synchronization between IT department and admissions system. </li>
          <li> Implement near real-time portal systems, used by all colleges and departments on campus. </li>
          <li> Implement authentication system for career exploration site - <a href="http://planyouradventure.net" target="_blank" class="text-muted">My Academic Plan</a> used by hundreds of middle schools and high schools. </li>
          <li> Alter MySQL databases for storage efficiency. </li>
          <li> Enhance existing software with modification or replacement. </li>
          <li> Conduct thorough testing of solutions implemented and occasionally present implementation to client. </li>
      </ul>
      </p>
  </div>
</div>

<div class="panel panel-primary">
  <div href="#education_and_skills" data-toggle="collapse" style="background-color: #37838F" class="panel-heading">Education and Skills</div>
  <div class="panel-body collapse" id="education_and_skills">
    <div style="padding-left:15px">
        <i class="fa fa-university" aria-hidden="true"></i> Bachelor of Science in Computer Engineering, <a href="http://ece.iastate.edu" target="_blank" class="small text-muted">Iowa State University</a>
    </div>
    <hr style="border-color:lightgray"/>
    <div>
    <div class="col-md-4">
        <strong>Programming</strong>
        <ul style="list-style-type:none; display:inline">
            <li> <i class="fa fa-cloud" aria-hidden="true"></i> LAMP Stack </li>
            <li> <i class="fa fa-object-group" aria-hidden="true"></i> Java, C# </li>
            <li> <i class="fa fa-code" aria-hidden="true"></i> Python, JS </li>
            <li> <i class="fa fa-database" aria-hidden="true"></i> MySQL, Hadoop </li>
        </ul>
    </div>
    <div class="col-md-4">
        <strong>Tools</strong>
        <ul style="list-style-type:none; display:inline">
            <li> <i class="fa fa-code-fork" aria-hidden="true"></i> Git, RCS </li>
            <li> <i class="fa fa-clone" aria-hidden="true"></i> JIRA, Trello </li>
            <li> <i class="fa fa-file-code-o" aria-hidden="true"></i> Atom & various others </li>
        </ul>
    </div>
    <div class="col-md-4">
        <strong>Platforms</strong>
        <ul style="list-style-type:none; display:inline">
            <li> <i class="fa fa-linux" aria-hidden="true"></i> Linux </li>
            <li> <i class="fa fa-android" aria-hidden="true"></i> Android </li>
            <li> <i class="fa fa-microchip" aria-hidden="true"></i> GAE </li>
        </ul>
    </div>
    </div>
  </div>
</div>

<div class="panel panel-primary">
    <div href="#projects" data-toggle="collapse" style="background-color: #37838F" class="panel-heading">Projects</div>
    <div class="panel-body collapse" id="projects">
    <h4 class="list-group-item-heading"> Twitter Data Analysis <span class="small text-muted">@ <a href="https://github.com/shahrushabh/Hadoop" target="_blank" class="text-muted">Hadoop Programs</a></span> </h4>
    <p class=list-group-item-text>
    <ul style="list-style-type:circle;">
        <li> Tools utilized: Hadoop, HDFS, MapReduce  </li>
        <li> Implemented custom JSON input format to convert tweets into JSON format  </li>
        <li> Implemented MapReduce Jobs to extract relevant information </li>
        <li> Analyze specific attributes of using MapReduce, such as Popular HashTags, Most followed users </li>
    </ul>
    </p>
    <hr  style="border-color:lightgray"/>
    <h4 class="list-group-item-heading"> Mars Rover <span class="small text-muted">@ <a href="https://github.com/shahrushabh/Embedded_Systems" target="_blank" class="text-muted">Embedded Systems</a></span> </h4>
    <p class=list-group-item-text>
    <ul style="list-style-type:circle;">
        <li> Tools utilized: C, PuTTY, Matlab, and iRobot with Micro-controller ATMega128 </li>
        <li> Performed accurate sensor calibration, used to detect obstacles standing in the way of robot  </li>
        <li> Implemented data transmission with Serial Communication Interface over Bluetooth </li>
        <li> Implemented graphical interface with real-time updates from sensor in Matlab  </li>
    </ul>
    </p>
    <hr  style="border-color:lightgray"/>
    <h4 class="list-group-item-heading"> Attendance <span class="small text-muted">@ <a href="https://github.com/shahrushabh/AndroidProjects" target="_blank" class="text-muted">Android Application</a></span> </h4>
    <p class=list-group-item-text>
    <ul style="list-style-type:circle;">
        <li> Tools utilized: Android SDK, Java, Google Endpoints, Maps, Git </li>
        <li> Location based attendance tracking application </li>
        <li> Implemented application preferences for GPS usage </li>
        <li> Developed Endpoints API for this application </li>
    </ul>
    </p>
    <hr  style="border-color:lightgray"/>
    <h4 class="list-group-item-heading"> Quick Quote Program <span class="small text-muted">@Van Gorp Corporation</span></h4> 
    <p class=list-group-item-text>
    <ul style="list-style-type:circle;">
        <li> Lead the software team through design and implementation of WPF application </li>
        <li> Gather requirements and specification from client </li>
        <li> Research possible solutions that fit the specs </li>
        <li> Carry out implementation and testing </li>
        <li> Encourage code review and pull requests within the team </li>
    </ul>
    </p>
    </div>
</div>
</div>

<script>
    $(function(){
        $('a[href="/experience"]').parent().addClass("active");
        $('#summary').collapse('show');
        $('#toggle').click(function(){
            if($('#toggle').html() == 'COLLAPSE ALL'){
                $('#toggle').html('EXPAND ALL');
                $('.panel-body').each(function(){
                    $(this).collapse('hide');
                });
            }else{
                $('#toggle').html('COLLAPSE ALL');
                $('.panel-body').each(function(){
                    $(this).collapse('show');
                });
            }
        });
    });
</script>