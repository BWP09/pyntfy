# PyNtfy (PyNotify)
This module allows you to easily send notification using [ntfy](https://ntfy.sh/).
This includes multiple helper funtions

More info can be found at the [ntfy docs](https://docs.ntfy.sh/publish/)

## Example
```
ntfy(
  topic_url = "YOUR_TOPIC_URL",
  content = "example text",
  title = Title("example title"),
  priority = Priority(2)
)
```
