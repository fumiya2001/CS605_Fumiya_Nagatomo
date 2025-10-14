## Test Document

Suppose we create an instance, bst = BinarySearchTree(), and then we try to apply following method to this instance.


| Test Case | Test Method |Input (Name, Phone Number) | Expected Output | Actual Output | 
|-----------|--------------------------------------|-----------------|---------------|-------|
| 1 | insert|'Alice','555-1234' | - | - | 
| 2 | insert |'Bob','555-2345' | - | - |
| 3 | insert |'Charlie', '555-3456' | - | - |
| 4 | search| 'Alice',-- | '555-1234' | '555-1234' | 
| 5 | search|'David',-- | Name not found | Name not found |
| 6 | inorder_traversal |--,--| Alice : 555-1234 <br> Bob : 555-2345 <br> Charlie : 555-3456 | Alice : 555-1234 <br> Bob : 555-2345 <br> Charlie : 555-3456|
| 7 | delete|'Alice', -- | Bob : 555-2345 <br> Charlie : 555-3456 | Bob : 555-2345 <br> Charlie : 555-3456|
