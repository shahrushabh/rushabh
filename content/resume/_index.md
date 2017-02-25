+++
title = "Resume"
date = "2017-01-01T00:00:00Z"
math = false
highlight = false

# Optional featured image (relative to `static/img/` folder).
[header]
image = ""
caption = ""
+++
<button id="toggle" type="button" class="btn btn-default" style="float:right;">EXPAND ALL</button><br/>

<div class="panel panel-primary">
  <div href="#summary" data-toggle="collapse" class="panel-heading">Summary</div>
  <div class="panel-body collapse" id="summary">
  <p class="left-space">As a Software Engineer, I have built various software, mobile and webapplications. I am passionate about developing sophisticated software and implementing creative ideas. I work well in team environment and can also handle individual projects with minimal supervision. Through professional and class work, I gained excellent verbal skills and positive attitude that can help with effective contribution.</p>
  </div>
</div>

<div class="panel panel-primary">
  <div href="#professional_experience" data-toggle="collapse" class="panel-heading">Experience</div>
  <div class="panel-body collapse" id="professional_experience">
      <h4 class="list-group-item-heading"> Web Developer: Iowa State University <small class="text-muted"><i><a href="http://admissions.iastate.edu" target="_blank">Office of Admissions</a></i></small>
      </h4>
      <p class="list-group-item-text">
      <ul>
          <li> Develop web applications on LAMP stack in an agile environment. </li>
          <li> Implement PHP scrips that preforms batch jobs that syncs data between IT department and admissions system. </li>
          <li> Implement real time portal systems that is utilized by all colleges and departments on campus. </li>
          <li> Implement account creation, authentication system for career exploration - <a href="http://planyouradventure.net" target="_blank">My Academic Plan</a>. </li>
          <li> Alter MySQL databases for storage efficiency. </li>
          <li> Enhance existing software with modification or replacement. </li>
          <li> Conduct thorough testing of solutions implemented and occasionally present implementation to client. </li>
      </ul>
      </p>
  </div>
</div>

<div class="panel panel-primary">
  <div href="#education_and_skills" data-toggle="collapse" class="panel-heading">Education and Skills</div>
  <div class="panel-body collapse" id="education_and_skills">
    <a href="http://ece.iastate.edu" target="_blank">Iowa State University, College of Engineering</a> | Ames, Iowa
  </div>
</div>

<div class="panel panel-primary">
    <div href="#projects_and_experiments" data-toggle="collapse" class="panel-heading">Projects and Experiments</div>
    <div class="panel-body collapse" id="projects_and_experiments">
    <h4 class="list-group-item-heading"> Quick Quote Program: Van Gorp Corporation </h4>
    <p class=list-group-item-text>
    <ul>
        <li> Lead the software team through design and implementation of WPF application </li>
        <li> Gather requirements and specification from client. </li>
        <li> Research all possible solutions that fit the specs. </li>
        <li> Carry out implementation and testing. </li>
        <li> Encourage code review and pull requests within the team. </li>
    </ul>
    </p>
    </div>
</div>

<script>
    $(function(){
        $('#summary').collapse('show');
        $('#toggle').click(function(){
            if($('#toggle').html() == 'COLLAPSE ALL'){
                $('#toggle').html('EXPAND ALL');
                $('.collapse').each(function(){
                    $(this).collapse('hide');
                });
            }else{
                $('#toggle').html('COLLAPSE ALL');
                $('.collapse').each(function(){
                    $(this).collapse('show');
                });
            }
        });
    });
</script>