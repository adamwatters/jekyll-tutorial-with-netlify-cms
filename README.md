### Netlify CMS Jekyll Notes

currently not button for jekyll here https://www.netlifycms.org/docs/start-with-a-template/, but this exists https://templates.netlify.com/template/jekyll-with-netlify-cms-boilerplate/

theres this, https://www.netlify.com/blog/2015/10/28/a-step-by-step-guide-jekyll-3.0-on-netlify/, but I don't think
Netlify CMS wants to assume someone is using netlify

this is a nice theme https://github.com/daviddarnes/alembic-kit

really, this is the competition https://forestry.io/docs/guides/developing-with-jekyll/,
slack channel: https://forestry-community.slack.com/messages/C78GWHNKE/convo/C6G82P1PX-1543868550.001600/

followed this https://jekyllrb.com/docs/step-by-step/10-deployment/
`_posts` has special meaning
`_collections` has special meaning

1. Start with Jekyl step by step https://jekyllrb.com/docs/step-by-step/01-setup/
2. choose path - Github/Netlify

NETLIFY

1. this is a very good start
   https://blog.mvp-space.com/10-steps-to-configure-jekyll-with-netlify-as-a-cms-d754d73ea731

2) i forgot this step for a long time https://app.netlify.com/sites/jekyll-with-netlify-cms/settings/identity#git-gateway
   resulting in
   `GET https://jekyll-with-netlify-cms.netlify.com/.netlify/git/settings 404`
   `API_ERROR: Your Git Gateway backend is not returning valid settings. Please make sure it is enabled.`

GITHUB

1. Take a [few special steps](https://github.com/jekyll/jekyll/issues/332) to get the site running on Github pages https://adamwatters.github.io/netlify-cms-jekyll/blog.html
2. add base admin dir

3) `Error loading the CMS configuration Config Errors: config should have required property 'collections' config should have required property 'media_folder' config should have required property 'media_library' config should match some schema in anyOf Check your config.yml file.`
