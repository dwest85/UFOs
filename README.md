# UFOs

# Overview of Project
* The purpose of this analysis was to imrpove upon the searching filter to include extra parameters for filtering our table data: City entry, State entry, Country entry, and Shape entry. This helps fine tune our filtering of the sighting information to make our web app even more powerful. 

# Results
* The web app user will now be able to fine tune their filtering results to access more precise information involving past UFO sightings. I also updated our previous code to now make the filtering process update without hitting a button. Each filter parameter will update our list by simply entering the information. This is possible by using a d3.selectAll with an "input" on "change" line.

* ![input_change_pic](https://github.com/dwest85/UFOs/blob/main/images/input_change_pic.PNG)

* We were then able to remove the button function completely from our index.html.

* ![button_comment_out](https://github.com/dwest85/UFOs/blob/main/images/button_comment_out.PNG)

* An example picture of performing a filter search:
* ![filter_search](https://github.com/dwest85/UFOs/blob/main/images/filter_search.PNG)

# Summary
* One major drawback with the current version of the web app is that the information entered into the filters are still case sensitive. This makes the filtering process very exact and can pose problems for the end-user when filtering the table data. 

* Future update recommendation # 1
* I recommend adding a feature to this web app to make the filtered data non-case sensitive. This will make the information filtering process much smoother for the end-user.

* Future update recommendation # 2
* I also recommend on adding a scraping feature to ensure the newest data is pulling into the table so the end-user has access to the most current sighting information.

* ![app_index](https://github.com/dwest85/UFOs/blob/main/images/app_index.PNG)