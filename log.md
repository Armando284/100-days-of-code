# 100 Days Of Code - Log

### Day 0: August 9, 2023

**Today's Progress**: Added function composition method to my terminal logs formatter project, it still doesn't work.

**Thoughts:** I am really struggling with function composition and `this` in TypeScript, but I am making progress, after much effort I have something that at least works similar to Chalk and that's amazing.

**Link to work:** [Log Formatter](https://www.npmjs.com/package/format-logs)

**Link to work:** [Github Commit](https://github.com/Armando284/format-logs/commit/d781e47a8f64dc298148cbd5e51822f4e72abb97)

### Day 1: August 10, 2023

**Today's Progress**: Fixed function composition on my npm package for terminal styling.

**Thoughts:** It was really time consuming to find a way for the composition main function to work and get it's inner methods since those are added after creating the function with Object.defineProperty, the idea was to use a getter for each text style so it can grow and the builder pattern to join everything up.

**Link to work:** [Log Formatter](https://www.npmjs.com/package/format-logs)

**Link to work:** [Github Commit](https://github.com/Armando284/format-logs/commit/afd852be61364421a0bfe17312f61658f51edd44)