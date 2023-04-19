## $PATH

Dari mana terminal tau kalo fungsi *echo* itu untuk print?

$PATH lah jawabannya. Dia akan mencari dari yang paling kiri dari variabel PATH

**Append dan Prepend to path**

```
PATH=$PATH:/some/dir
PATH=/some/dir:$PATH
```
modifying $PATH bisa di .bash_profile (untuk permanen)

