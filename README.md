# Assignment 2 - Investree

## GitHub Project
https://github.com/Indrapurnomo29/Assignment-2

## Gist Project (Step how to run)
https://gist.github.com/Indrapurnomo29/c7bc9d8e2a36b6d51349c324edb6a874

## Base URL
https://api.publicapis.org/entries

## Services
### GET/entries
## Parameters

| No | Parameter     | Data Type | Description                             | Required |
| -- | ------------- | --------- | --------------------------------------- | -------- |
| 1  | title         | string    | name of entry (matches via              | No       |
|    |               |           | substring -i.e. "at" would return "cat" |          |
|    |               |           | and "atlas")                            |          |
| 2  | description   | string    | description of entry (matches via       | No       |    
|    |               |           | substring)                              |          |
| 3  | auth          | string    | auth type of entry (can only be         | No       | 
|    |               |           | values matching in project or null)     |          |
| 4  | https         | string    | return entries that support HTTPS or    | No       |
|    |               |           | not                                     |          |
| 5  | cors          | string    | CORS support for entry ("yes", "no",    | No       | 
|    |               |           | or "unknown")                           |          |
| 6  | category      | string    | return entries of a specific category   | No       |


