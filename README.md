# Geo-View

Geo-View project - Braintoy

To run, you will need to install `pipenv` on your machine using `pip install pipenv` command.
Then run `pipenv install` to install the dependencies.

All LAS files should be inside `/Data`. (Not included because file size is too large)

Run `pipenv shell` first then use `python app.py` command for both the frontend and backend apps in corresponding folders.

Completed:

- `/list` endpoint for retrieving the list of files.
- `/list/<filename>` endpoint for retrieving file data.
- Implemented Blueprint for modular application.
- Basic frontend app (tables for file info and plots)
- Frontend: Added navbar.
- Pre-processing of data for Numpy NaN values that results in invalid JSON object.

To do:

- Fix plot (width, height)
- Toggle plots for curves based on selection.
- Make changes to the data.
- Pagination for list of files.
- Add other necessary pages.
- TBD
