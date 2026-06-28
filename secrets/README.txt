Create a file named `node_seed` in this directory.

Its entire content must be one line:

SXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXX self

Replace the S... value with the secret seed produced by:

docker run --rm stellar/stellar-core:27.0.1-3368.6e768de7a.jammy gen-seed

Never commit the real `node_seed` file to source control.
