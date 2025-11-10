# ssstest

<H2>SSS-Test: SQL Scalability Simulation recipe</H2>

<i>Load testing on a shoestring</i>

(The SSS Test was originally published on SourceForge in 2006 and is still visible at http://ssstest.sourceforge.net/)


<br>Have you ever encountered any of the use-cases described below?</br>

<ul dir="auto">
<li><p dir="auto">
Developers are given an assignment to quickly put together a new report to be run by 30 concurrent users. In unit testing, response time for a single user running this report is acceptable. 
The question is, of course, if that will still hold true if the other 29 users jump in.
Any way to give a substantiated answer without actually asking 30 end-users to run this new report?
<br>Perhaps an even more important question is whether slamming this new report on an already busy system might have any adverse affect of degrading system performance?</br>
</p></li>

<li><p dir="auto">
The new module is going through a unit testing, and you, as a DBA, are asked to evaluate any (hopefully none) potential adverse effects on the already existing and carefully tuned modules. What course of action would you suggest?
</p></li>

<li><p dir="auto">
No new code path, same old well-known system, but now due to a recent merger there are expected to be at least 20% inrease in the number of concurrent users. 
You are asked whether your system can handle the load. How do you go about answering this question?
</p></li>
</ul>
	
<p>If the questions I asked above don't sound unusual to you in your line of work, then I hope you may find the SSS-test presented here of some value:</p>
<p>
<br>1/ "SQL Testing through Scalability with Respect to Concurrent User Count: A Simulation Recipe" 
	<br><a href="http://ssstest.sourceforge.net/SSStest_Dali_ScalabilityTesting.pdf"><font face="geneva, arial, sans-serif" size="2"><b>Original paper on Source Forge</b></font></a> 
	<br><a href="http://ssstest.sourceforge.net/SSStest_Dali_ScalabilityTesting.pdf"><font face="geneva, arial, sans-serif" size="2"><b>Local copy</b></font></a> 
<br>2/ <a href="http://ssstest.sourceforge.net/sss_test.tar.gz"><font face="geneva, arial, sans-serif" size="2"><b>SSS-Test</b></font></a>
<br>3/ <a href="http://www.tns-0.com"><font face="geneva, arial, sans-serif" size="2"><b>Additional resources</b></font></a>, including hiperlinked html-based documentation, test results and appendixes mentioned in the documentation (after being redirected to the www.tns-0.com web site, follow the SSS-Test link)
</p>



