# windows

## Qemu

C:\Program Files\qemu\qemu-system-x86_64.exe" -m 6096 -boot d -enable-kvm -net nic -net user,hostfwd=tcp::1022-:22,hostfwd=tcp::9021-:9021,hostfwd=tcp::9022-:9022,hostfwd=tcp::8080-:8080,hostfwd=tcp::9663-:9663,hostfwd=tcp::9664-:9664,hostfwd=tcp::3000-:3000  -hda C:\Users\egune\Documents\my-image.img -accel hax -nographic
