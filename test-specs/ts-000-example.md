# Specification version number

2013-01-19-000

# Specification name

Bob's example quality test spec!

# Test preconditions

Example: an internet connection
Alternate example: An x.25 network connection

# Expected impact

Example: Ability to detect TCP MITM

# Expected inputs

## Import document or import data format

## Data specification version number

Question: Do we really nead a version number for the data specification?

## Semantics

For example:

one ip address port combination per line separated by colon (ex.
127.0.0.1:9050)

# Test description

Describe what operations are done on the input to produce the output.
Implementation details that could potentially affect the end result should also
be mentioned here.

# Expected output

## Parent data format

This is the base data format(s) that this test will adhere to (it is
implicit that it will follow df-000-base).

## Required output data

This is data that should be part of the base dataformat without which the
test cannot properly be interpreted.

## Data specification version number

Question: Isn't this implicit in the test specification number, is there a reason
why we should have two versions one for the data format and one for the
test specification? Would changing the dataformat not imply changing the
test version number?

## Semantics

List the extra keys that will be part of the report that are not part of
the parent data format. Be sure not to have keys that clash with the
parent data format.

## Possible conclusions

Based on the ouput data what conclusions can you draw?

## Example output sample

## Expected Post-processing efforts

Question: What exactly is meant by this? Is this meaning the possible
difficulties that a person doing post-processing may encouter?

# Privacy considerations

There are a few!

# Packet capture considerations

We capture all packets on the interface foo for bar units of time.

# Other notes

Bikesh{r}ed!

