## ABOUT
##### Python script templates for running and monitoring of Zeppelin notes from CLI.
##### For details [Apache Zeppelin REST API].
## Usage
##### **IMPORTANT:** HOSTNM and PNO variables must be changed to the actual Zeppelin *hostname* and *port number* values in these scripts. 
<pre><code>
lszepp
</code></pre>
##### Lists all the notes stored on the target Zeppelin server.
<pre><code>
runzepp
</code></pre>
##### Runs the target Zeppelin note. The note must be run once through the browser, prior to running of this CLI command, for any web UI input variable settings to take effect.
<pre><code>
runzepp-async
</code></pre>
##### Runs the target Zeppelin note in the asynchronous mode (note status can be monitored by *chkzepp*). The note must be run once through the browser, prior to running of this CLI command, for any web UI input variable settings to take effect.
<pre><code>
chkzepp
</code></pre>
##### Reports the current paragraph execution status or the final status of the target Zeppelin note.

[Apache Zeppelin REST API]: https://zeppelin.apache.org/docs/0.10.0/usage/rest_api/notebook_repository.html
