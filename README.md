**Forked from [Academic Pages](https://github.com/academicpages/academicpages.github.io)**

## Running locally (Mac)

### 1. Install required tools
```bash
brew install ruby
brew install node
gem install bundler
```

### 2. Install project dependencies
From the root of the repository:
```bash
bundle install
```

If you encounter permission errors, install gems locally:
```bash
bundle config set --local path 'vendor/bundle'
bundle install
```

### 3. Start the local server
```bash
bundle exec jekyll serve -l -H localhost
```

Open the site at:
```
http://localhost:4000
```
