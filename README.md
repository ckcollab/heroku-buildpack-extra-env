# heroku-buildpacks-extra-env

Exports env vars so your application code can access them

## Usage
The first step is to add the Heroku [multi buildpack](https://github.com/heroku/heroku-buildpack-multi) to your app.
Next, create a `.buildpacks` file in your app repo or edit an existing file. Add this to the file:

	https://github.com/ckcollab/heroku-buildpack-extra-env.git

## Variables available

### `CURRENT_BRANCH_NAME`

current github branch name

### `CURRENT_COMMIT_SHA`

current commit sha

## License
MIT
