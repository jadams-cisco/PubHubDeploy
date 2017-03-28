# PubHub Deploy 

The objective of this repo is to make the deployment of PubHub docs for internal use painless. Push an HTML file with the PubHub JavaScript included, then visit https://devnetapic.cisco.com/SBPH/[NAME]. Instructions outlined below: 

## Instructions

1. Publish a PubHub document, and copy the publication script. 
2. Create an html file with the PubHub doc with a name that represents your PubHub doc. ex. sandbox-internal-doc
3. Input this HTML code: 

``` html
<!DOCTYPE html>
<html>
<body>
<!-- Input PubHub JavaScript below -->

<!-- Input PubHub JavaScript above -->
</body>
</html>
```

4. Insert the PubHub JavaScript between the commented tags
5. Save the .html file you created in the **templates** folder
6. Push the new .html file to Master on the repository
7. Visit https://devnetapic.cisco.com/SBPH/[NAME] where [NAME] is the html file you've created **Without the .html suffix**

Contact Jacob Adams (jacoadam@cisco.com) with any questions. 

