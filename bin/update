#!/bin/bash

SYNC=`xbps-install -S`
UPDATES=`xbps-install -Mnu | wc -l`
[[ $UPDATES -eq 0 ]] && exit 0

echo "${UPDATES}"
exit 0
