# WWW Project Honeypot

This is the home for the Honeypot project.

## Testing changes locally

To perform changes locally and test them before creating a pull request, do this:

### Get the files

```bash
git clone https://github.com/OWASP/www-project-honeypot.git
```

### Install dependencies

```bash
bundle install
```

### Run locally

```bash
bundle exec jekyll serve --incremental
```

#### Add images you wish to link to in assets/images

Link would be in form `/assets/images/<filename.ext>`
