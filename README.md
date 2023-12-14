# XpathTIPS

### 1. Partial Text Search:
```xpath
//div[contains(text(), 'partial_text')]
```
### 2. Search by Attribute:
```xpath
//div[@attribute='value']
```
### 3. Multiple Conditions:
```xpath
//div[@class='class' and @id='identifier']
```
### 4. Search by Index:
```xpath
//div[1]   <!-- first element -->
//div[last()]   <!-- last element -->
//div[position()=2]   <!-- second element -->
```
### 5. Search by Parent Element:
```xpath
//div[@class='parent_class']//div[@class='child_class']
```
### 6. Search by Child Element:
```xpath
//div[@class='parent_class']/div[@class='child_class']
```
### 7. Search by Previous Sibling:
```xpath
//div[@class='current_class']/preceding-sibling::div
```
### 8. Search by Next Sibling:
```xpath
//div[@class='current_class']/following-sibling::div
```
### 9. Search by Case-Insensitive Text:
```xpath
//div[lower-case(text())='text_in_lower_case']
```
### 10. Search by Text Start:
```xpath
//div[starts-with(text(), 'start_of_text')]
```
