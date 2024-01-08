---
id: coding-examples
title: React Coding Examples
---

# React Coding Examples

This section demonstrates coding examples related to our project.

## Coding Question 1

**Task:**

Create a functional component named `Counter` that uses the `useState` hook to manage a counter. Implement two buttons - one to increment the counter and another to decrement it. Display the current count on the screen.

**Example:**

```jsx
import React, { useState } from 'react';

const Counter = () => {
  const [count, setCount] = useState(0);

  return (
    <div>
      <p>Count: {count}</p>
      <button onClick={() => setCount(count + 1)}>Increment</button>
      <button onClick={() => setCount(count - 1)}>Decrement</button>
    </div>
  );
  
};
