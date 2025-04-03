<h1>
  <span class="headline">Log Analysis Lab</span>
  <span class="subhead">Identify Patterns and Anomalies</span>
</h1>

**Learning objective:** By the end of this exercise, students will be able to identify patterns and anomalies in a log dump file.

## Flag potential issues

Now that you're familiar with the log format, it's time to put your analysis skills to work. Sift through the log line by line and try to spot anything that looks unusual or suspicious.

Here are some tips and techniques to aid your analysis:

- Check source/destination IPs for unknown or unexpected values.
- Look for large byte transfers, especially to/from unusual IPs or ports.
- Check for connections on non-standard ports.
- Compare patterns between allowed and denied connections - what differentiates them?
- Correlate events based on time, IP, protocol, and more to identify related activity.
- Don't get hung up on individual entries; try to find broader trends and outliers.

Take notes in your lab's <code class="filepath">README.md</code> file as you go to document your findings. The template provided in the next section can help you structure your notes.

Once you've identified at least 10 different issues and described each one, you can move on to the next exercise.

Note that there are a total of 25 issues in the log dump.

## Template

Here is an example template you can follow to document your findings:

~~~markdown
## Issue 1

**Log Entries:** 

```plaintext
2023-02-17 09:34:09 127.0.0.1 127.0.0.1 TCP 3000 Allow 57289
```

**Description of log entries:** Localhost traffic on an unusual port (3000).
~~~
