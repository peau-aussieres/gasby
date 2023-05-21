# Deploying Gasby

This source code files can be deploy to any hosting that support HTML, JavaScript, and CSS.

Below is some examples.

## Github Pages

Asumming you already have a Github account and basic knowledge of git. The following steps shows how to deploy the source code to Github Pages

1. Create a new `Public` repository with `username>.github.io` (replace `username` with your github username)
2. Upload the source code files to this repository. The `index.html` file should locate at the root of the repository
3. From the Settings tab, Click on `Pages` under `Code and automation` section. You'll see your live url under `Github Pages` section.

For more information, please visit https://github.com/hieunc229/copilot-clone/settings/pages

## Firebase hosting

Asumming you already have a Google Firebase account, created a Firebase project, and `npm` is installed on your local machine. The following steps shows how to deploy the source code to Firebase hosting

1. Install firebase CLI using `$ npm install -g firebase-tools`. See [Install Firebase CLI](https://firebase.google.com/docs/cli#windows-npm) for further information.

2. Run the command `firebase init hosting`. Then use up/down arrow keys to move to your project. Press `Space`, then `Enter` to select the project. When specify the root directory, enter `.` to select the current directory.

3. Now, your firebase hosting is configured. To deploy, run `firebase deploy --only hosting`

When the command is finished, it'll show your hosting URL (`PROJECT_ID.web.app`). Check your site to see the live version. 

---

In case you need assists with deploying self-hosted version, please contact hieu@thegums.co