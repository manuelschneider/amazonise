# Amazonise your Debian Image

It's just a quick and dirty script to create an amazon-ami from
a raw-image (incl partition-table) with debian.

Maybe someone else could need it. However some script-parts are
from https://github.com/tomheady/ec2debian/wiki/64bit-ebs-ami-pvgrub,
and I included the ec2-tools to avoid the hazzle of downloading them.

If there are any legal conflicts, please contact me - they're not
intentionally.

As always, it's provided 'as is' without any warranties.

Example usage:

    $ sudo ./amazonise image.raw

Bugfixes, optimisations, more supported platforms are welcome :o)
