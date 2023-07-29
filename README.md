# Greetingcard_React
import React from 'react';

// Define a functional component called GreetingCard
function GreetingCard(props) {
  // Use props to customize the greeting message
  const { name, message, color } = props;

  // Return a JSX element that displays the greeting card
  return (
    <div style={{ backgroundColor: color, padding: 10 }}>
      <h1>Hello, {name}!</h1>
      <p>{message}</p>
    </div>
  );
}

// Export the component so it can be used elsewhere
export default GreetingCard;
