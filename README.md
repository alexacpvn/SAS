# SAS 

FIRST STEPS WHEN WRITING CODE FOR A REPORT

Clear the log and Results Viewer - 
  ONLY APPLIES TO THE EDITOR - not the enterprise guide - This is also optional - not required to continue happily coding! 

When we work in SAS, we want to keep track of the submitted code and output. Therefore, it is crucial to know your log and results viewer well. Because they can get messy. Your log can be filled with millions of lines. Also, your results viewer can contain much information you do not need. Therefore, it is convenient clean up the mess so you can stay focused on what is important. 
Let us look at how to clear the SAS log with simple code. I use the DM Statement with LOG ‘CLEAR’ as arguments to clear everything in the current log. 

/* Clean log and output */
dm log "clear";
dm output "clear";
Clear Results Viewer

Summary
It is often very convenient to clear out the things you do not need, whether it is in your log, results viewer or some third place. 
