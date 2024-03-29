# Whatsapp-text-analyzer

The script reads an exported WhatsApp chat and tries to vizualize insights that are mined from the data.

To see interactive storyboard in the notebook [use this link](https://nbviewer.jupyter.org/github/hdev7/Whatsapp-text-analyzer/blob/master/text%20analysis.ipynb)

### What's in store
- Feature extraction from unstructured data using Regex
- Working with Emoticons
- Word tokenizing and removing stop words
- Using WordCloud
- Visual story via tableau
- Currently support below chat pattern:
 ```python
    "14/10/18, 11:16 - Contact Name: this is a message"
    "2/30/18, 2:07 AM - Contact Name:  Test👌"
    "[30/12/18 4.59.25 PM] Nama User: 🙏test"
    "[06/07/17 13.23.30] ‪+62 123-456-78910‬: <media omitted>"
  ```


### Requirements
- Python
```python
pip install pandas emoji matplotlib numpy wordcloud 
```

### Getting chat source
#### Android:
- Open a chat/group chat
- Tap on trhee dots oh the top right
- Tap "More"
- Choose "Export chat"
- Choose "Without Media"

#### iOS
- Open a chat/group chat
- Tap on contact name/group name on the top to see the details
- Scroll down to find "Export Chat" menu
- Choose "Without Media"


