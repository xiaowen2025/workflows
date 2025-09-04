# Write
write python playwright script /scripts/e2e.py to start the app, screenshoot the key UI pages to demo the major features of the app.  

Mock any expensive processes such as tts. Consider introduce env DEMO=true.

Screenshots should be saved under docs/demo/screenshots/.

Then draft a demo documentation in .md under /docs/demo with screenshoot images embeded.  

Read the docs/prd.md to highlight useful features for each screen.

structure like this.  

/docs/demo

- demo.md
/images  

- 01_init.png
- ...  

{{
# Introduce Project

Highlevel Goal, main value.   

Example Input and Output.

## Features

## Highlights 

}}

# Update  

Run /scripts/demo.py, update the script if needed. 

# set up 

uv pip install playwright
uv run playwright install-deps
uv run python scripts/demo.py



uv run playwright install