# Setup

This is a single file Rails demo app for utilizing Cloud Native Buildpacks with Kamal.

1. `git clone git@github.com:nickhammond/kamal-buildpacks-rails.git`
2. `bundle install`
3. Install the Pack CLI `brew install buildpacks/tap/pack`
4. Add your Docker personal access token to _.kamal/secrets_  as `KAMAL_REGISTRY_PASSWORD=dckr_pat_x`
5. Update the host IP address in _config/deploy.yml_ to point to your server
3. Run `bundle exec kamal setup` to deploy the app