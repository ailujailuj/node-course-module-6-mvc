This is an example of MVC pattern.

Model:
- Responsible for representing your data;
- Responsible for managing your data (saving, fetching, ...);
- Doesn't matter if you manage data in memory, files, databases;
- Contains data-related logic.

View:
- What the user sees;
- Shouldn't contain too much logic (Handlebars!).

Controller:
- Connects Model and View;
- Should only make sure that the two can communicate (in both directions).