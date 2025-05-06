# llm-archives

### Instructions

Click the "Use this template" button for this repository and choose "Create a new repository". You can give it the same name (llm-archives).

Once it's ready, go to [Groq](https://console.groq.com/keys) and follow the directions to get an API key. You'll need to login (or create an account if you don't have one).

Copy the API key value and then click on the Settings of your GitHub repository and click on "Secrets and variables" on the left side, then choose "Codespaces"

Click the green "New Repository Secret" button and paste your API Key into the "Secret" box, then put GROQ_API_KEY in the Name box above it. Click "Add Secret" and click on the name of the repository to return to the main page.

From there, click the green "Code" button and create a new Codespace in the Codespaces tab.

In the Terminal type the following: pip install requests groq and hit enter.

Then type: python get_stories.py

You should see a file called cns_maryland_posts.json appear. Let's look at it. It contains some details of the past 10 CNS stories.

Back in the Terminal, type: python entity_extraction.py and watch the output.

### Evaluation for JOUR389W
My news organization story did very well when pasting in here to get the information it needed. The people, places, and organizations are tools that my news organization could use for its archives by extracting them from documents and tagging them for future research, sourcing, or story development. This process can also reveal patterns, for example, showing where certain types of hazards or violence tend to occur, if particular neighborhoods are repeatedly mentioned, or if certain families or entities are consistently involved in incidents. Over time, this can help identify systemic issues or emerging trends worth investigating further.
