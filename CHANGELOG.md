## 0.1.0

* feature: add list selection
* feature: add checkbox selection
* feature: add colors
* improvement: extract style into its own module
* improvement: implement interface for all prompts under Ask module
* improvement: moved prompt rendering to IOHelper
* improvement: separate the looping of user input out of the list and move it to the IOHelper
* improvement: separate selector from item rendering
* improvement: separate list rendering from processing
* bugfix: don't do anything if checkbox has no items
* bugfix: don't render the list if there is no item in it
* bugfix: create the Inquirer module first, before including any of its implementations
* bugfix: make simple checkbox selected colored
* bugfix: select checkbox items based on space keypress
