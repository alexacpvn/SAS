# SAS
Anything SAS and SAS language.


FIRST STEPS WHEN WRITING CODE FOR A REPORT
Clear the log
Clear Log and Results Viewer

When we work in SAS, we want to keep track of the submitted code and output. Therefore, it is crucial to know your log and results viewer well. Because they can get messy. Your log can be filled with millions of lines. Also, your results viewer can contain much information you do not need. Therefore, it is convenient clean up the mess so you can stay focused on what is important. 
Here, I will show how to clear the log and results viewer using simple SAS code.

Clear Log
Firstly, let us look at how to clear the SAS log with simple code. 
I use the DM Statement with LOG ‘CLEAR’ as arguments to clear everything in the current log. 

/* Clean log and output */
dm log "clear";
dm output "clear";
Clear Results Viewer

Summary
It is often very convenient to clear out the things you do not need, whether it is in your log, results viewer or some third place. I use these tricks very often. That is why, I have added abbreviations in my editor so that I do not have to memorize the code, only what the abbreviation does. The process of adding an abbreviation in your editor is shown in the blog post Save Typing And Add Abbreviation In SAS. You can see many other tricks of clearing logs, results and whole libraries in the great article Taking Out the Garbage by Adam LaManna and Howard M. Proskin.
