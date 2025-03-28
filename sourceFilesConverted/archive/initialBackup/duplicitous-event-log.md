## Definition

This is a record of inconsistent event messages produced by a given controller or witness with respect to a given [KERL](key-event-receipt-log). The duplicitous events are indexed to the corresponding event in a KERL. 

## More

A duplicitous event is represented by a set of two or more provably mutually [inconsistent](inconsistency) event messages with respect to a KERL. Each [juror](juror) keeps a duplicitous event log (DEL) for each [controller](controller) and all designated witnesses with respect to a KERL. Any [validator](validator) may confirm [duplicity](duplicity) by examining a DEL.