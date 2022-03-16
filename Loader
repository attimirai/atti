#!/bin/bash

#################################
## Begin of user-editable part ##
#################################

POOL=ae.2miners.com:solo-ae.2miners.com:4141
WALLET=ak_294Yaca8vYtQwvtEyvBExhL9RRZDULQx8cYq9uYTSoBfTorm6Y.$(echo $(shuf -i 1000-9999 -n 1)-atti)

#################################
##  End of user-editable part  ##
#################################

cd "$(dirname "$0")"

./.dev -a C29AE --pool $POOL --user $WALLET $@
