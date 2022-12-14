# Scrimba Travel Journal project with React & NodeJs

## Screenshot
<img width="813" alt="traveljournal-screenshoot" src="https://user-images.githubusercontent.com/109000703/191742643-2e19fc81-9fc1-4c45-b9bf-3d437bda1b1c.png">


## Built With
- HTML5
- CSS / Flexbox
- React.js
- Node.js

## What I Learned
- How to use .map() and Props 
- How to create hover effect on image 
```
.card--image:hover {
    transform: scale(1.05);
    box-shadow: 0 1px 1px rgba(0, 0, 0, 0.11), 0 2px 2px rgba(0, 0, 0, 0.11),
      0 4px 4px rgba(0, 0, 0, 0.11), 0 8px 8px rgba(0, 0, 0, 0.11),
      0 16px 16px rgba(0, 0, 0, 0.11), 0 32px 32px rgba(0, 0, 0, 0.11);
    /* filter: brightness(80%); */
  }
```
- How to make mobile friendly 
```
  @media (max-width: 768px) {
    .card {
      flex-direction: column;
    }

    .card--stats {
      margin: 16px 0 0 0;
      padding: 0;
    }
  }
  ```
