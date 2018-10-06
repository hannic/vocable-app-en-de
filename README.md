## vocable-app-en-de

##### Table of Contents  
[About](#about)  
[Customize](#customize)  


<a name="about"/>

## About

It is a simple vocable web app to represent your collected data 
- Data source will be provided by a Google spreadsheet, so while there will more additions the app will get the data by demand. 
- The Google Spreadsheet file has two columns with words in English and its Translation in German. The translation will be displayed with a delay. 

- <img src="https://github.com/hannic/vocable-app-en-de/blob/master/spreadsheet-vocable.png" width=600>


<a name="customize"/>

## Customize

*Bring your vocable collected (in a csv, Excel file) into the web for an interactive experience*

**index.html:**

  ```javascript
  
  // replace <url to csv> with your csv 
  function myFunction(){
      var uri = <url to csv> 
      //e.g.  'https://docs.google.com/spreadsheets/d/e/2PACX1vQJcScro25wgFYAOQ0XEQYg6WccqhkY7WStqxKrJWKK_yq7sTmXMXARUsbrd4T8PIfsCToXNhzlwRou/pub?output=tsv';

      ...
  }
  ```


