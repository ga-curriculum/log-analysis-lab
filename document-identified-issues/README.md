<h1>
  <span class="headline">Log Analysis Lab</span>
  <span class="subhead">Document Identified Issues</span>
</h1>

**Learning objective:** By the end of this exercise, students will be able to identify and document potential security issues in a log dump file.

## Exercise

You should now have a list of at least 10 items you've flagged as potentially suspicious or problematic. In this exercise, you'll document these in more detail.

For each issue, create a record including:

- The relevant log snippets.
- A description of the log entry.
- An explanation of why it appears suspicious.
- An analysis of the potential impact if it is indeed malicious.
- Possible explanations or root causes (for example, misconfiguration, malware, attack, and so on).

The template provided below expands on the template from the previous exercise. Use it to structure your findings. You can add additional fields if you think they would be helpful.

By the end of this exercise, you should have a well-structured document detailing at least 10 potential security issues you've uncovered through your analysis. This artifact demonstrates your ability to interpret the log data and connect it to real-world security concerns.

## Template

Here is an example template you can follow to document your findings:

~~~markdown
## Issue 1

**Log Entries:**

```plaintext
2023-02-17 09:34:09 127.0.0.1 127.0.0.1 TCP 3000 Allow 57289
```

**Description of log entries:** Localhost traffic on an unusual port (3000).

**Reason for concern:** Potential rogue process or misconfiguration.

**Potential impact:** Could indicate data exfiltration or unauthorized access.

**Possible explanations:** Misconfiguration, command and control attack, or legitimate service.

~~~
