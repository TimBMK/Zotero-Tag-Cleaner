# Zotero-Tag-Cleaner
A python tool for cleaning up the tags in your zotero library

If one is trying to maintain a clean zotero library, tags are very helpful in ordering and quickly accessing literature for certain interests. However, keeping tags meaningful can be challenging, especially for shared libraries. If you went through the trouble of making a list of meaningful tags to use only to have your library flooded by Zotero's auto-tagging function, this tool helps restore order by deleting all the tags not approved by whitelists. 

Since this is a function Zotero is missing, I decided to upload the Jupyter notebook I used to maintain order in our research group's library. It uses Zotero's open API via the pyzotero package. Output from the notebook maintained as examples.

IMPORTANT: This tool will delete tags permanently. Back up your zotero library before use in case you delete the wrong tags!
