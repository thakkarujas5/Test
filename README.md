# '/tasks'

## Parameters:-

  1) isCompleted (optional): If present, filter the tasks by completion status. If set to true, return only completed tasks. If set to false, return only incomplete tasks.
  2) sortBy (optional) - if present, sorts tasks based on the specified property. To sort in ascending order, simply provide the property name. To sort in descending order, prefix the property name with a -. For example, to sort by priority in descending order, use sortBy=-priority.

##Example Request:- GET /tasks?isCompleted=true&sortBy=-priority
  
  
