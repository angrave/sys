## Comments ##
In the video I say "C has no boolean type." That's a bit of a half-truth.
If you're using a more modern specification of C, C99 or newer, you can now `#include <stdbool.h>`
which includes a definition of a type `bool` but it just
defines 'true' to be integer 1 and 'false' to be integer 0!
