#!/bin/bash

#File containing list of IDs that need attributes
IDs=$1
#File containing attributes
ATTRIBUTES=$2
while read attribute
  do
    grep $attribute $ATTRIBUTES
  done<$IDs
