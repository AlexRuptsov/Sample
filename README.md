# Sample

```javascript
   function addItem() {
                let text = document.getElementById('newItemName').value;
                var li = document.createElement("li");
                li.id= text;
                li.appendChild(document.createTextNode(text));
                document.getElementById("items").appendChild(li);
                document.getElementById("newItemName").value = "";               
            }
```            
