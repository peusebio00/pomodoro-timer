# pomodoro-timer

Program built with Python to help with applying the Pomodoro Technique - it uses the Python GUI Tkinter module, and displays a user-interactive screen with an active timer and buttons for the user to control their actions;

Functionalities are:
- The timer starts at 00:00;
- There are two buttons: Start and Reset;
- When the user clicks on "Start", the initial "Timer" label changes to "Work" and the time goes to 25:00 mins, and begins counting down one second at a time, displaying each second as it passes;
- For every complete 25 mins "Work" cycle, a green tick is added on to the bottom part of the screen so the user can keep track of how many cycles they've gone through;
When timer reaches 00:00, the top label that previously displayed "Work" will then display "Break" - timer also goes to 05:00 mins and starts counting down to 00:00;
- When it reaches 00:00, a new "Work" cycle commences, so timer goes back to 25:00 mins.

- Upon completing 3 cycles of "Work" (25 mins) followed by "Break" (5 mins), the 4th one will include a 20 min-long "Break" rather than just the standard 5 mins; So, effectively, every 4 cycles, the user is rewarded with a longer break for productivity and rest reasons

- Lastly, the Reset button:
- When clicked, everything is reset to zero, as the name suggests: timer goes back to 00:00, top label goes back to displaying "Timer" rather than "Work" or "Break" as it is effectively awaiting user-action, and checks on the bottom of the screen are reset to zero - hence, ready to be used again.

Enjoy!
