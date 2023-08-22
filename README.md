# Key Questions:

## React Day 4
- Why are fetch and useEffect oftentimes used together?
  - Putting a fetch call in a useEffect is common because it either lets the application load relevant data upon the first render, OR if specified it can control when it’s time to load data again (depending on the variable value in the dependency array). It gives further control into when a data load should happen to promote efficiency.
- What is the significance of the dependency array in the useEffect hook?
  - The dependency array determines when the code inside the useEffect hook will be run. If the array is empty, the useEffect code will only run one time. If the array has a variable inside, the useEffect code will run every time the variable value changes.
- What are some use cases of useEffect?
  - Fetching data 
  - Having something happen when a timer hits a certain number of seconds
  - Adding custom animations when a variable is updated (or something like that)

