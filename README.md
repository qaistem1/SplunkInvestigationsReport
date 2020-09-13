# Splunk Investigations Report
The search joins the Investigations rest search with the notables macro search in order to get information like: investigation name, colloborators, creation date, closure time, response time, investigation notable events, investigation notable events urgency etc.

NOTE: the two searches has been matched using the "title" field in the investigations search and the "notable_xref_id" field in the notables search.
