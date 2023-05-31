A repo to run some analytics plots over argo floats app download reports.  

A github workflow is set up to (every 15 days) :
- configure the GCS account 
- retrieve install reports 
- install conda env
- run the notebook with papermill
- save the executed notebook in html as the doc page
..
