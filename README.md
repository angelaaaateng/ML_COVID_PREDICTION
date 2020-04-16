# ML_COVID_PREDICTION

- Team Folder: https://drive.google.com/drive/u/2/folders/1zf3p0ORcRn2ngabcy2aFOnOvCt8DiOkR

- Initial Data Source: https://news.abs-cbn.com/news/03/15/20/list-health-departments-list-of-confirmed-covid-19-cases?fbclid=IwAR1w1pcW5zoyL46ihgThrmQi4HUqcVibPXHBKEPptrxXGdT-cZAZpow2syo

- Data Science Philippines: https://www.facebook.com/groups/datasciencephilippines
- DSP Dataset Opensource: https://docs.google.com/spreadsheets/d/16g_PUxKYMC0XjeEKF6FPUBq2-pFgmTkHoj5lbVrGLhE/edit#gid=801084642
- DOH Dataset PH: https://docs.google.com/spreadsheets/d/1BLbrvgjkBWxr9g73xX9DLOqmbmuYyKc-_b8jIxCX1uo/edit#gid=286423021
- Philippine Statistics Agency for Population Data: https://psa.gov.ph/products-and-services/publications/philippine-statistical-yearbook
- Philippine Open Data for Demographic Information: https://data.gov.ph/?q=search%2Ftype%2Fdataset&query=population&sort_by=changed&sort_order=DESC


### Process:
- Data Cleaning
  - Geography Data:
    - Downloaded PH Case # Data
      - Used OpenRefine to clean 'Location' column
    - Downloaded DOH C Case Data
      - Used OpenRefine to clean 'Location' column and extract first element (city)
        - Clustering Methods: (https://github.com/OpenRefine/OpenRefine/wiki/Clustering)
          - key collision method, fingerprint function
          - key collision method, metaphone3
          -
