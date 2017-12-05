# klm
the og IVA based bug; just, dont set the world on fire
# how IVA works
this bug uses IVA (indirect variable assignment) to crash Safari on iPhone.
so it:
* stores the text in document.title
* assigns location.href to document.title; hopefully bypassing checks
* crashes MobileSafari
