# LOG oriented Print

<i>v0.1.0</i>

### Overview
Regular print statements that are souped up with tags like warning, info, error.

### Usage

```python
import logger as log

log.title(input:str):
    #print input as it is with *'s above and below 

log.info(input:str):
    # print input preceeded by "[ INFO ]"

log.error(input:str):
    # print input preceeded by "[ ERROR ]"

log.warning(input:str):
    # print input preceeded by "[ WARNING ]"
```
## Sample code

```python
import logger as log

log.title("This is a Title")
log.info("INFO MSG")
log.error("ERROR MSG")
log.warning("WARNING MSG")
```

## Sample outputs

```
*********************************************
               This is a Title               
*********************************************
[ INFO    ]  INFO MSG
[ ERROR   ]  ERROR MSG
[ WARNING ]  WARNING MSG
```

More features coming soon