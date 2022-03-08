# Research Data Manager Program
## Setup
A research article PDF electronic filing system is antiquated and difficult to use.
## Problem
Users waste precious time hunting documents spread across small overlapping categorical folders to track down each PDF manually, then must visually scan the document to determine by ad hoc metrics if those contents match their needs.
## Options
### File Organization
- Decentralized file subfolder organization system [current]
- Centralize research documents within a single folder
### File Search and Sort
- Manual [current]
- Implement algorithm using keyword lists
- Implement algorithm using key:vale metadata
### File Data Organization
- Encode minimal article data in PDF file names [current]
- Encode article data as object literals
- Encode article data as JSON 
### File Data Updates
- None [current]
- Manually update data
- Implement webscraper to update data
## Solution
Centralize research documents within a single folder. Design network of article, author, organization, and grant metadata to be accessed by HTML card catalog. Create a JavaScript algorithm to accept catalog search input, filter documents based on metadata 	keywords, sort results by match strength, then output a PDF hyperlinks ranked list.
## Goals
- Lessen the personnel-hour burden of research pdf information retrieval
- Strike an acceptable compromise between backend system automation and frontend user input flexibility
- Make the system easy to use and hard to break
## Features
### Critical Implemented
### Critical Unimplemented
- ddddd
### Wishlist Unimplemented
- ddddd
## Development
### Process
- flowchart
### Architecture
- class chart
### Schedule
```mermaid
gantt
    dateFormat  YYYY-MM-DD
    title       Adding GANTT diagram functionality to mermaid
    excludes    weekends
    %% (`excludes` accepts specific dates in YYYY-MM-DD format, days of the week ("sunday") or "weekends", but not the word "weekdays".)

    section A section
    Completed task            :done,    des1, 2014-01-06,2014-01-08
    Active task               :active,  des2, 2014-01-09, 3d
    Future task               :         des3, after des2, 5d
    Future task2              :         des4, after des3, 5d

    section Critical tasks
    Completed task in the critical line :crit, done, 2014-01-06,24h
    Implement parser and jison          :crit, done, after des1, 2d
    Create tests for parser             :crit, active, 3d
    Future task in critical line        :crit, 5d
    Create tests for renderer           :2d
    Add to mermaid                      :1d
    Functionality added                 :milestone, 2014-01-25, 0d

    section Documentation
    Describe gantt syntax               :active, a1, after des1, 3d
    Add gantt diagram to demo page      :after a1  , 20h
    Add another diagram to demo page    :doc1, after a1  , 48h

    section Last section
    Describe gantt syntax               :after doc1, 3d
    Add gantt diagram to demo page      :20h
    Add another diagram to demo page    :48h
```
### Responsibilities
- keyed list

## Reference Code
- [Template Literals](https://www.youtube.com/watch?v=DG4obitDvUA&t=2069s)
