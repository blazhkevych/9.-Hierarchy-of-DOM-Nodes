# 9.-Hierarchy-of-DOM-Nodes

Write a client script that allows you to dynamically create a multi-level bulleted list. The web page should provide an interface that allows you to perform the following actions:
* add a new element to the end of the list (input type="text");
* insert a new list item at the given position (input type="text");
* change the text of the list item (input type="text");
* add nested list (input type="text");
* remove list item.

![image](https://github.com/blazhkevych/9.-Hierarchy-of-DOM-Nodes/assets/65856963/a6ed25bb-3f8d-4d8c-86c5-7da596deee43)


The list constructor works in the following way.
* When you click on the "Add new list" button, a bulleted list with one element is created.
* To change the text of a list element, select the corresponding radio button (input type="radio"), enter a new text, and then "click" on the list element.
* To add a new element to the end of the list, select the appropriate radio button (input type="radio"), enter the text, and then "click" on any element of the list located at the same level.
* To insert a new list item at a specific position, select the appropriate radio button (input type="radio"), enter the text, and then "click" on the list item before which you want to insert the new item.
* To add a nested list, select the appropriate radio button (input type="radio"), enter the text, and then "click" on the list element for which the nested list will be a child. An attempt to create a nested list for an element that already has a child list should be prevented.
* To delete a list item, select the corresponding radio button (input type="radio"), then click on the list item to be deleted. Note that deleting a list element deletes all of its child elements.
