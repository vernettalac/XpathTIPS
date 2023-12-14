# XpathTIPS

## Description
This repository provides useful XPath tips for effective element selection in HTML documents. Whether you're a beginner or an experienced user, these XPath tips will help you navigate and locate elements more efficiently.

### 1. Partial Text Search:
```xpath
//div[contains(text(), 'partial_text')]
```
Use when searching for an element with partial text content.

### 2. Search by Attribute:
```xpath
//div[@attribute='value']
```
Applicable when locating an element based on a specific attribute value.

### 3. Multiple Conditions:
```xpath
//div[@class='class' and @id='identifier']
```
Useful when combining multiple conditions for precise element selection.

### 4. Search by Index:
```xpath
//div[1]   <!-- first element -->
//div[last()]   <!-- last element -->
//div[position()=2]   <!-- second element -->
```
Employ when selecting elements by their position in the document.

### 5. Search by Parent Element:
```xpath
//div[@class='parent_class']//div[@class='child_class']
```
Use to locate a child element within a specific parent element.

### 6. Search by Child Element:
```xpath
//div[@class='parent_class']/div[@class='child_class']
```
Appropriate for finding a child element directly under a parent.

### 7. Search by Previous Sibling:
```xpath
//div[@class='current_class']/preceding-sibling::div
```
Helpful when searching for the preceding sibling of a given element.

### 8. Search by Next Sibling:
```xpath
//div[@class='current_class']/following-sibling::div
```
Useful for locating the following sibling of a specified element.

### 9. Search by Case-Insensitive Text:
```xpath
//div[lower-case(text())='text_in_lower_case']
```
Apply when matching text content irrespective of case.

### 10. Search by Text Start:
```xpath
//div[starts-with(text(), 'start_of_text')]
```
Use to find elements where the text content starts with a specific string.

