# Lab 2 version control #

## Task J i ##
Link to the file
https://github.com/CDHUppsala/Gallica_pdf/blob/7623d738c5efb188a1b87b64e11cad28eb7e05b4/get_pdf.py

## Task J ii ##
The file get_dpf.py uses the following libraries:
- 'urllib.request'
- 'urllib.error'
- 'urllib.parse'

## Tas J iii ##
Here are a few examples of how the libraries are used in the code.
opener = urllib.request.build_opener()
except urllib.error.HTTPError as e:
urllib.request.urlretrieve(pdf_link, foldername+"/"+pdf_name,headers=headers)


