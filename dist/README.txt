PTLiar v2.0.11

* simple instruction:

1. put the torrent files you want to fake upload into folder 'up_torrents' (optional)
2. put the torrent files you want to fake download into folder 'down_torrents' (optional)
3. run PTLiar.exe      (if you are using windowsx86 binary)
   or python PTLiar.py (if you are using source)

* full usage:

usage: PTLiar [options]
options:
    -h    help, print this message
    -l    print the list of supported clients
    -m    maximum upload bandwidth, in KB/s, (default: 2048)
    -M    maximum download bandwidth, in KB/s, (default: 1024)
    -s    maximum speed per torrent, in KB/s, (default: 400)
    -c    client to emulate (default: uTorrent2.2.1, see -l)
    -t    timer, in hours (default: 8964)
    -p    fake seeding port number (default: random)
    -e    enable IPv6 (default: disabled)
    -z    enable 'zero-rate' (recommended)
    -n    disable 'scrape' (default: enabled)
    -f    skip some sleep
    -v    verbose
press [Ctrl+C] for exit

Example: python PTLiar.py -m 2048 -M 5120 -c uTorrent3.0
    max-down-speed set to 5MB/s,
    max-up-speed set to 2MB/s,
    using client uTorrent3.0

homepage: http://PTLiar.com
email: s@PTLiar.com