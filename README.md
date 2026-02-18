# unfeed
Client modifications for various websites to facilitate time saving &amp; intentional internet use.

Script to Test CSS Injection
```
const style = document.createElement('style');
style.textContent = `
/* your CSS here */
`;
document.head.appendChild(style);
```