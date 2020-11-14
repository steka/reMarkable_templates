To use these templates on the [reMarkable](https://remarkable.com/), you have to:

1. Copy both the png-, and svg-files to the `/usr/share/remarkable/templates/` folder on the reMarkable, using for example [WinSCP](https://winscp.net/) or [FileZilla](https://filezilla-project.org/).

2. Edit `/usr/share/remarkable/templates/templates.json` by adding the following at the appropriate place according to the JSON-format (this can also be done from within [WinSCP](https://winscp.net/)) or [FileZilla](https://filezilla-project.org/).
```
    ,
    {
      "name": "Whitelines lines",
      "filename": "Whitelines_lines",
      "iconCode": "\ue9a8",
      "categories": [
        "Lines",
        "Custom"
      ]
    },
    {
      "name": "Whitelines squares",
      "filename": "Whitelines_squares",
      "iconCode": "\ue99e",
      "categories": [
        "Grids",
        "Custom"
      ]
    }
```
