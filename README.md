# Unit2.FreelancerForum

# Freelancer Management Program Documentation

## State

Here, we define variables representing the state of our program:

- `names`: Array of freelancer names.
- `occupations`: Array of freelancer occupations.
- `freelancers`: Array to store freelancer objects.
- `maxFreelancers`: Maximum number of freelancers allowed.

## Example Usage

```javascript
const newFreelancer = createFreelancer();
console.log(newFreelancer);
console.log(freelancers);
```
## Interval for Adding Freelancers
The program uses setInterval to call createFreelancer every 1000 milliseconds (1 second). The interval can be stopped using clearInterval(addFreelancerIntervalId).

## Functions
averagePrice()
Calculates and returns the average starting price of all freelancers.

render()
Updates the DOM to reflect the current state:

Renders a table with columns (Name, Occupation, Starting Price).
Updates the average starting price.

## createFreelancer()
Creates a new freelancer with a random name, occupation, and starting price.
Appends the new freelancer to the freelancers array.
Calls the render function.
Stops adding freelancers if the maximum limit (maxFreelancers) is reached.

# DOM Structure

The table is rendered within an element with the ID "freelancer".
The average starting price is displayed within an element with the ID "average".
Usage
Run the program to dynamically add freelancers.
The table and average starting price will be updated in real-time.
The interval will stop when the maximum number of freelancers is reached.

