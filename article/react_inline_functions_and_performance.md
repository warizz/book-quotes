# React, Inline Functions, and Performance

## Premature optimization is the root of all evil

>Ask any performance expert and they will tell you not to prematurely optimize your program. All of them. Yes, every single one of them. 100% of people with deep performance experience will tell you not to prematurely optimize your code.

...

>Not only can premature optimization explode development time while hurting code cleanliness, it can even backfire and cause performance problems as it did for LABjs. Had the author been measuring, rather than just imagining performance issues, he would have saved development time, had cleaner code, and better performance.

# In summary

>- Write your code naturally, code to the design.
- Measure your interactions to find slow paths. [Here’s how.](https://reactjs.org/blog/2016/11/16/react-v15.4.0.html#profiling-components-with-chrome-timeline)
- Use `PureComponent` and `shouldComponentUpdate` only when you need to, skipping prop functions (unless they are used in lifecycle hooks for side-effects).

>If you really believe that premature optimization is bad practice, then you won’t need proof that inline functions are fast, you need proof that they are slow.
