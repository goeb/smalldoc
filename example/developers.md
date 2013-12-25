# Developers' Corner


## REST API
The requests are driven by the Query String:

Examples:

- `colspec=status+release+assignee`

    The properties specified by colspec shall be displayed in the table.

- `sort=aaa-bbb+ccc`

    The specified properties shall drive the sorting order (`+` for ascending order, and `-` for descending order).

- `search=hello world`

    Full text search on all properties and messages.

- `filterin=status:open&filterin=assignee:John Smith&filterout=release:undefined`

    'filterin' and 'filterout' may be specified several times on the query string.

- `format= text | html | csv`

    The default format is HTML.

- `full=1`

    This makes sense only for the `issues` pages, and makes the page display all issues and their contents on the page.


