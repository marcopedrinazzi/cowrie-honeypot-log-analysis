# Cowrie Honeypot Log Analysis with Jupyter Notebook
This is a Jupyter Notebook to help you analyze Cowrie honeypot logs, it was created to support the analysis I did in the blog post https://medium.com/@pedrinazzim/weekend-plan-cowrie-honeypot-log-analysis-afd707f801f6

This notebook has the purpose to simplify the analysis of the Cowrie Honeypot logs in case the honeypot is not configured to send data to an ELK-stack, Splunk, etc. The analysis of Cowrie logs is structured in 5 categories. Each category contains a subset of the event ids that cowrie honeypot can log and overall the five categories contain all the possible event ids.
The categories are the following:
- Logins
- Commands
- File uploads and downloads
- Sessions
- Misc

**This notebook requires the following API:**
```
- IPInfo (IP map Report)
```

**This notebook works with the following packages:**
```
- os
- pandas
- datetime
- requests
- folium
```

Upload all your logs files in a folder (I used `cowrie` as a name but you can change it as you like) and watch Jupyter do a bit of magic ;)

If you prefer to do the analysis in another way, the .csv files for every event id that cowrie can log are saved as well.

Any contribution, feedback, or idea is welcome.
