<br/>
<div align="center">

A curated list of awesome Ruby Security related resources.

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

_List inspired by the [awesome](https://github.com/sindresorhus/awesome) list thing._

Supported by: [GuardRails.io](https://github.com/apps/guardrails)

</div>
<br/>

# Contents
- [Tools](#tools)
- [Educational](#educational)
- [Other](#other)
- [Contributing](#contributing)

# Tools

## Web Framework Hardening

- [secure-headers](https://github.com/twitter/secure_headers) - Manages application of security headers with many safe defaults.
- [Rack::Attack](https://github.com/kickstarter/rack-attack) - Middleware for blocking and throttling requests.

## Multi tools

- [hawkeye](https://github.com/hawkeyesec/scanner-cli) - Multi purpose security/vulnerability/risk scanning tool supporting Ruby, Node.js, Python, PHP and Java.
- [Salus](https://github.com/coinbase/salus) - Multi purpose security scanning tool supporting Ruby, Node, Python and Go.
- [GuardRails](https://www.guardrails.io) - A GitHub App that gives you instant security feedback in your Pull Requests.
- [Snyk](https://snyk.io) - Continuously and automatically finds & fixes vulnerabilities for Ruby and other languages.

## Static Code Analysis

- [brakeman](https://github.com/presidentbeef/brakeman) - A static analysis security vulnerability scanner for Ruby on Rails applications.
- [rubocop-gitlab-security](https://gitlab.com/gitlab-org/rubocop-gitlab-security) - A set of rules to extend rubocop with additional security rules.
- [dawnscanner](https://github.com/thesp0nge/dawnscanner) - A static analysis security scanner for ruby applications. It supports Sinatra, Padrino and Ruby on Rails frameworks.
- [git-secrets](https://github.com/awslabs/git-secrets) - Prevents you from committing secrets and credentials into git repositories.
- [DevSkim](https://github.com/Microsoft/DevSkim) - DevSkim is a set of IDE plugins and rules that provide security "linting" capabilities. Also has support for CLI so it can be integrated into CI/CD pipeline.
- [ban-sensitive-files](https://github.com/bahmutov/ban-sensitive-files) - Checks filenames to be committed against a library of filename rules to prevent storing sensitive files in Git. Checks some files for sensitive contents (for example authToken inside .npmrc file).
- [rails_best_practices](https://github.com/flyerhzm/rails_best_practices) - A static code analyzer for Ruby on Rails applications that finds - among other things - common patterns that might lead to security vulnerabilities.
- [Rails Application Routes Parser](https://gist.github.com/Splint3r7/198a3f8f19f20c28fff44993427012c3) - A script that print out ruby on rails application routes/URLs. 

## Vulnerabilities and Security Advisories

- [bundler-audit](https://rubygems.org/gems/bundler-audit) - Patch-level verification for Ruby apps.
- [ruby-advisory-db](https://github.com/rubysec/ruby-advisory-db) - Open source database of security advisories that are relevant to Ruby libraries.
- [GemScanner](https://github.com/Splint3r7/GemScanner) - GemScanner identifies depreciated versions of gems in your ruby on rails project.

# Educational

## Hacking Playground

- [RailsGoat](https://github.com/OWASP/railsgoat) - A vulnerable version of Rails that follows the OWASP Top 10 http://railsgoat.cktricky.com .
- [DeleteMe](https://github.com/rietta/DeleteMe) - Educational insecure Rails application.

## Articles & Guides

- [Rails Security Guides](https://guides.rubyonrails.org/security.html) - The essentials to read when dealing with Rails Applications.
- [Securing Ruby and Rails Apps](https://www.occamslabs.com/blog/securing-your-ruby-and-rails-codebase) - Applying static code analysis and dependency checking in your CI/CD pipeline.
- [OWASP Ruby on Rails Cheatsheet](https://www.owasp.org/index.php/Ruby_on_Rails_Cheatsheet) - This Cheatsheet intends to provide quick basic Ruby on Rails security tips for developers. It complements, augments or emphasizes points brought up in the rails security guide from [rails core](https://guides.rubyonrails.org/security.html).
- [Rails security checklist](https://github.com/eliotsykes/rails-security-checklist) - 🔑 Community-driven Rails Security Checklist.
- [Attacking Ruby on Rails Applications](http://www.phrack.org/issues/69/12.html#article) - Phrack article by [joernchen](https://twitter.com/joernchen) on finding security vulnerabilities in Rails applications.
- [Zen Rails Security Checklist](https://github.com/brunofacca/zen-rails-security-checklist#memcached-security) - A well-documented Rails security checklist.
- [Rails security best practices](https://github.com/ankane/secure_rails) - A good overview of usefull things to look out for when working with Rails.
- [Securing Rails Application from developers perspective](http://hassankhanyusufzai.com/securing-rails-application/) - A detailed blog on Ruby on Rails security from developers perspective that contains OWASP Top & other application issues with fixes /  recommendation and fix codes.

## Newsletters
- [Security for Developers](https://www.getrevue.co/profile/devsecops) - Newsletter catering towards developers and covering many languages. 

# Other

## Reporting Bugs

- [Ruby Bug Bounty Program](https://hackerone.com/ruby) - Found a bug in the Ruby language? Report it there.
- [Ruby Security Updates](https://www.ruby-lang.org/en/security/) - Follow the latest security announcements.

# Contributing

Found an awesome project, package, article, other type of resources related to Ruby Security? Send me a pull request!
Just follow the [guidelines](/CONTRIBUTING.md). Thank you!

---

say _hi_ on [Twitter](https://twitter.com/pxlpnk)

## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](http://creativecommons.org/publicdomain/zero/1.0/)
