#!/usr/bin/env bash

# kubectl context switch plugin
# version 0.1

if test $# -eq 0; then
	echo "* " `kubectl config current-context`
	kubectl config get-contexts -o name
elif test $# -eq 1; then
	kubectl config use $1
else
	echo bad args
	exit 1
fi
