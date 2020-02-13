# elementary-os-tricks
Some trick for elementary os (debian based os)

1. Cannot open pdf with Pdfstudio (URIs issue):
Fix: Exec=/home/$user/bin/pdfstudio/pdfstudio2019 %F
add %f %F %u %U parameter at the end.
