# On - Demand Session

- Identifying the State
- Updating the styles based on State



# Displaying the Projects List
- When User Clicked on TabItem Corresponding category of projects should be filtered and displays in the UI


  # tabId             ProjectList=>filteredProjectList

- STATIC
- RESPONSIVE
- Dynamic

# What will be the state?
# Identify the state?
- State=>The state is a Js object in which we store the Component's data that changes over the time.
- state => render()

- Here both Active Tab Item and Project List are changing over the time.

- activeTabId holds the tabId of the active tab
- filteredProjects holds the projects filtered by category

# Maintaining the State

- Every time when user clicked on TabItem, activeTabId will be updated and render() is called.
- So we can filter projectList direclty in render() using activeTabId





