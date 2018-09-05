# Table Builder for CSV
The Table Builder for CSV is a simple plugin that creates HTML table from csv file.                    
                         
## Installation                            
Download table-builder-for-csv.zip file and upload it to wordpress plugins folder, then activate it. If you download release file,
you should extract it to find table-builder-for-csv.zip file.


## Donate to support us                                     
                                                                   
[![Donate with Bitcoin](https://en.cryptobadges.io/badge/small/16f1DStB3YG3R4BMTa1zGYRxN9i7FAqtUX)](https://en.cryptobadges.io/donate/16f1DStB3YG3R4BMTa1zGYRxN9i7FAqtUX)
                                                   
  [![Donate with Bitcoin](https://en.cryptobadges.io/badge/big/16f1DStB3YG3R4BMTa1zGYRxN9i7FAqtUX)](https://en.cryptobadges.io/donate/16f1DStB3YG3R4BMTa1zGYRxN9i7FAqtUX)                                                                          
                                                              
## Description                                    
                            
The Table Builder for CSV creates HTML table from csv file. It provides pagination and search filter capabilities for created table. Also,
you can customize settings of created table and define new captions for columns headers. For using this plugin, you should place your csv
files in the Wordpress uploads folder.                                   

To use this plugin, after activation of the plugin, you should place [table_builder_for_csv] shortcode in your posts.

**Attributes for the shortcode:**                                                            
                                            
1)  src: Path to csv file from uploads folder( For example, if test.csv file is in the Wordpress uploads folder, then src="test.csv".)
                                                    
2)  id: Assign an ID for each shortcode in content. (For example id="1")                              
                                       
3)  captions: You can define custom captions for columns headers of table. If you want to use first row of the csv file as columns headers,
    don't use this attribute. Separate each header with @#. (For example captions="col1@#col2@#col3"                      
                                                
4)  searchbox: Assign true (searchbox="true"), if you want to use search filter for table. (Default is false)                 
                                 
5)  rows: Number of rows per page for table pagination. (for example, rows="5". Default is 10)                   

6)  textalign: Text alignment for table.                         
                           
7)  headerbg: Background color for columns headers.                          
                      
8)  headercolor: Text color of columns headers.                        
                            
9)  pagebg: Background color for pagination links.                            
                             
10) pagecolor: Text color of pagination links.                                 
                                      
11) pageactive: Background color for active pagination link.                               
                                
12) pagehoverbg: Background color for pagination links on mouse hover.                    
                              
13) pagehovercolor: Text color of pagination links on mouse hover.                
                                 
14) pagealign: Alignment for pagination links.                             

## Demo                 
                 

## The plugin page at wordpress.org: 

To vote or write a review for this plugin, please see following link:              

https://wordpress.org/plugins/table-builder-for-csv/
