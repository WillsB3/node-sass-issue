# node-sass-issue

Steps to reproduce:

1. Clone this repo.
2. `npm i`.
3. `gulp sass`

You will see compilation fail with an error. Now do this:

1. `npm uninstall node-sass`.
1. `npm install node-sass@3.4.2`.
1. `gulp sass`.

Note compilation now succeeds.
