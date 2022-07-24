## awk command to search lines that contain the date "2012-08-15"
 ``` console
 awk '/2012-08-15/ {print}' data.txt
 ```

 
 ## awk command that search in the 1st column the value equal to 30
 ``` console
 awk '$1 == 30 {print}' data.txt
 ```
