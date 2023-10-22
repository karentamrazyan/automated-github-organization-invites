# Automated Github Organization (and Team) Invites

Quickly host a webpage to allow people to click and receive an invite to your Github Organization and an (optional) default team.

<p align="center">
  <img src="auto-invites-example-ui.png"/>
</p>

### Features

* Validates submitted Github usernames
* Links in your Github Organization's avatar/image
* Lightweight
* Optionally auto-invite to a team inside the organization

### Get It Right Now

[![Deploy](https://render.com/images/deploy-to-render-button.svg)](https://render.com/deploy)

All you have to do is

1. Click **Deploy to Heroku**
2. Fill in the **Environment Variables** when prompted. These will be a *[Github Access Token](https://github.com/blog/1509-personal-api-tokens)*, which should have Organization privileges enabled, and a *GitHub Organization name*, and a *background color*. The choices are `{blue,green,grey,pink,red,white}`. If you don't enter one of those strings it defaults to 'white'. Lastly an optional *GitHub Organization team* can also be specified if you want your users to auto-join a default team.

#### All Done! Just share the Heroku App's URL to people and they'll be able to get themselves an invite to your organisation.

### Development

**Install:** 

```
bundle install
```

**Run Locally:**

```bash
ORGANIZATION_NAME="foo" GITHUB_TOKEN="bar"  bundle exec ruby web_app.rb
```

### Credit 

Thanks to *[Code, Applied To Life](https://medium.com/code-applied-to-life/automated-github-organization-invites-3e940aa27040#.sikfvzyaj)* for their efforts which were used as a base for this.
