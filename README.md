# RailsConf.today

Visit the site at https://2023.railsconf.today

## How do I add or update an event?

This repository is open source. You could fork it, make an update and send a pull request.

**OR**

You can send an email with the relevant details to railsconf2023@beflagrant.com

## How do I get an event removed?

The same way. ☺️


## More detailed update instructions
1. In the `src/_events/` directory create a new file.
1. The file name should be `04-[Day Number]-[24 Hour Time]-[Event Name]`
1. Enter the details for your event

```
---
layout: event
title:  "[Day of the Week] @ [Time] [Name of the event]"
date:   2023-04-[Day Number] [24 Hour Time] -0400
---

# {{ resource.data.title }} 

Describe your event!
```

That's it! Send a Pull Request.

