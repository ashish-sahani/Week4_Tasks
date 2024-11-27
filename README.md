"# Week4_Tasks"

Task 1: Working with STL Algorithms
We use STL algorithms to manipulate the controls.
std::for_each iterates and prints details of each control.
std::find_if is used to find specific controls based on conditions like ID or state.
std::count_if counts controls with specific states.
std::adjacent_find checks for consecutive controls with the same state.


Task 2: Iterating Through Containers and Finding Elements
Iterators are used to traverse through both dynamic and static widget containers.
std::copy is used to merge both containers into a new vector.
std::find is used to locate a specific widget in the combined list.


Task 3: Advanced STL Operations
std::fill sets all elements to a particular state.
std::generate generates random states for the controls.
std::transform changes the state of sliders to "invisible".
std::replace_if replaces "disabled" states with "enabled".


Task 4: Sorting, Searching, and Merging
std::sort is used to sort controls by their ID.
std::merge merges two sorted lists into one.


Task 5: Implementing Design Patterns in HMI
Singleton: HMISystem ensures only one instance is created.
Factory: ControlFactory creates a button.
Observer: Button observes the mode change and adjusts visibility.
