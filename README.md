# ssstest

SQL Scalability Simulation test

The SSS Test was originally published on SourceForge in 2006 and is still visible at http://ssstest.sourceforge.net/

<head>
   <meta content="text/html; charset=utf-8">
   <title> SSS-Test</title>
</head>


<div align="center"> <p><br><b><font face="geneva, arial, sans-serif" size="5" color="#0000FF">SSS-Test: SQL Scalability Simulation recipe </font></b> 
<br>Load testing on a shoestring</div>

    
        
    
       	<div align="center"><a href="http://sourceforge.net/"><img src="http://sflogo.sourceforge.net/sflogo.php?group_id=162757&amp;type=3" alt="SourceForge.net Logo" height="37" width="125" /></a>
	<br />This project is hosted at SourceForge.net.  <br />
	</div>



	<br> 
	Have you ever pondered about the situations described below?

        <p><IMG border=0 src=images/bullet.gif width=10 height=10>

	Developers are given an assignment to quickly put together a new report to be run by 30 concurrent users. In unit testing, response time for a single user running this report is acceptable. 
	The question is, of course, if that will still hold true if the other 29 users jump in.
	Any way to give a substantiated answer without actually asking 30 end-users to run this new report?
	<br>Perhaps an even more important question is whether slamming this new report on an already busy system might have any adverse affect of degrading system performance? 

        <p><IMG border=0 src=images/bullet.gif width=10 height=10>
	The new module is going through a unit testing, and you, as a DBA, are asked to evaluate any (hopefully none) potential adverse effects on the already existing and carefully tuned modules. What course of action would you suggest?

        <p><IMG border=0 src=images/bullet.gif width=10 height=10>
	No new code path, same old well-known system, but now due to a recent merger there are expected to be at least 20% inrease in the number of concurrent users. 
	You are asked whether your system can handle the load. How do you go about answering this question?
	
	<p>
	If the questions asked above don't sound unusual to you in your line of work you might find SSS-test of some value:
	<p>
	<br>1/ "SQL Testing through Scalability with Respect to Concurrent User Count: A Simulation Recipe" <a href="SSStest_Dali_ScalabilityTesting.pdf"><font face="geneva, arial, sans-serif" size="2"><b>paper (PDF)</b></font></a> 
	<br>2/ <a href="sss_test.tar.gz"><font face="geneva, arial, sans-serif" size="2"><b>SSS-Test</b></font></a>
	<br>3/ <a href="http://www.tns-0.com"><font face="geneva, arial, sans-serif" size="2"><b>Additional resources</b></font></a>, including hiperlinked html-based documentation, test results and appendixes mentioned in the documentation (after being redirected to the www.tns-0.com web site, follow the SSS-Test link)



