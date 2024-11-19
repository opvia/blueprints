# Templates for https://platform.seal.run 

## How to create templates in Seal
🎞️ See [Slack post](https://opram.slack.com/archives/C0509TH14DN/p1732025689004189) for video instructions

### 1. Create the template in Seal prod

Create any pages you want to templatein Seal, copy their ids and navigate to the admin panel. Go to the ‘Templates’ tab to input the ids of the pages. This will download a .zip folder to your computer containing a file for each template entity and a manifest.json file containing the top level information about the template (i.e name).
### 2. Upload the folder to this repository
Click ‘Add file’ (next to the green ‘Code’ button). Drag and drop the entire unzipped folder. Click on ‘propose changes’ and continue to make a pull request. Request review from anyone in the dropdown list.

### 3. Install the template
You can now install your template in any organisation. Just copy the template id and paste it as a parameter in the URL:
```
// replace YourOrgSlug with the org slug you are installing into
// replace TemplateIdGoesHere with your template id

https://platform.seal.run/o/YourOrgSlug?installTemplateId=TemplateIdGoesHere
```
