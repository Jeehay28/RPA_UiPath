# UiPath helpful tips
### How to sum a column in a data table
```
DTOnline.AsEnumerable.Sum(Function(x) Convert.ToDouble(x("Amount").ToString.Trim)).ToString
```
![image](https://user-images.githubusercontent.com/106166065/193394637-1e188779-caf0-4d9b-ba70-27b86829c1b0.png)

### :key: How to add a new line in a string
```
"Jeehay" + Environment.NewLine + "Park"
"Jeehay" + vbCrLf + "Park"
```

![image](https://user-images.githubusercontent.com/106166065/193395208-0e39a402-0631-4666-9007-202e0cc5925c.png)


### :key: How to count lines after extracting data
| Name            | Variable Type               | Description                     |
|-----------------|-----------------------------|---------------------------------|
|EditableText     | Uipath.Core.GenericValue    | Data from Screening Scraping    |

| Expression Editor                                        |
|----                                                      |
| EditableText.Split(Environment.NewLine).Length.ToString  |


### :key: How to Rename Sheet
- Package to Install : UiPath Team Excel Extensions Activities

![image](https://user-images.githubusercontent.com/106166065/193395279-77e1c337-a944-44a4-b43f-918803928dfc.png)



