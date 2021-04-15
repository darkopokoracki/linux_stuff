#!/bin/bash

systemctl is-active $1

if [ $? -ne 0 ]; then
    systemctl start $1
    echo "the $1 service has started successfully"
fi
