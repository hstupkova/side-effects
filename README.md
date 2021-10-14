# Side Effects

Learning project in an UDEMY course [React - The Complete Guide (incl Hooks, React Router, Redux)](https://www.udemy.com/course/react-the-complete-guide-incl-redux/) by Maximilian Schwarzmüller.

When we reload the application, our entire react script restarts and all variables from the last execution are lost. That's how the web and scripts and the browser works. 

It would be nice to store the data somewhere where it persists the reload. And even better than that, we also want to make sure that whenever this app does start, we check if the data was persisted. And if it is we log the user in automatically so that the user doesn't need to re-enter the details.