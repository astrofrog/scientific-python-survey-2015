Results for the 2015 Scientific Python Survey
---------------------------------------------

(this will be described in a soon-to-be-published blog post)

The results so far are contained in the ``results.json`` file in JSON format.
This file will be updated as the results of the survey are processed and
anonymized. The file contains a list of entries, where each entry is a response in the survey. At the moment, this contains 781 responses (there were a few more responses, but these had issues and will be added manually very soon). 

In version 1 (released 9th May 2015), each entry contains:

* ``experience``: how long the respondent has been using Python

* ``fields``: a list of fields that the respondent works in

* ``installations``: a list of dictionaries, where each dictionary
  corresponds to a single installation, which then gives the operating system
  and Python version (and in future, this will give the NumPy, SciPy, and
  Matplotlib versions)

* ``why_not_python3``: a list of reasons as to why the respondent is not using Python 3 (if that is the case)

Note that for several of the fields, one of the options is 'Other'.
Respondents were able to provide free-form text descriptions in these cases,
but these data need to first be cleaned up and anonymized before they can be
added here.

### Version history

9 May 2015: Initial version







