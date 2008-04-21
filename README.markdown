Altered Beast
=============

The popular rails-based Beast forum...

- updated for Rails 2.0
- using rspec/model_stubbing
- added a state machine for user logins
- built-in multi-site support
- spam protection from akismet/viking
- forum authorization rules (public/private/invitation)
- email and atom feed support
- xml/json API
- highline based easy console installer

help desired via git:

- $ git clone git://github.com/courtenay/altered_beast.git
- $ git submodule init`
- $ git submodule update`

INSTALLATION
------------

- download altered_beast
- install rails 2.0.x
- $ mkdir log
- $ rake tmp:create
- $ rake db:schema:load

First created user will be admin.
