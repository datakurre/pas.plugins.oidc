Changelog
=========


1.0a5 (unreleased)
------------------

- Update the plugin to make challenges.
  An anonymous user who visits a page for which you have to be authenticated,
  is redirected to the new require_login view on the plugin.
  This works the same way as the standard require_login page of Plone.
  [maurits]


1.0a4 (2023-01-16)
------------------

- Call getProperty only once when getting redirect_uris or scope.
  [maurits]

- use getProperty accessor
  [mamico]


1.0a3 (2022-10-30)
------------------

- Removed the hardcoded auth cookie name
  [alecghica]
- Fixed Python compatibility with version >= 3.6
  [alecghica]
- check if url is in portal before redirect #2
  [erral]
- manage came_from
  [mamico]

1.0a2 (unreleased)
------------------

- do userinforequest if there is a client.userinfo_endpoint
  [mamico]

1.0a1 (unreleased)
------------------

- Initial release.
  [mamico]
