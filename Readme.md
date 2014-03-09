# Bot to invade and spy on IRC networks

## INFO
- Written for Python 3

## TODO

- Read the Channel limit on first connection
- Add new connections if the limit is hit
- Specify a subnet to use IPs from
- Support IPv6
- Add NickServ Registration / Identification
- Use a Database
    - Save NickServ logins + mail addresses
    - Save channels
        - Track channel keys
- Use IMAP for NickServ account registration
- Add webinterface
    - Channel logs
    - Nick tracking (stalking)
    - Configuration
        - Add / remove channels
        - Blacklist channels (e.g. Auto-Kline channels on freenode)
        - Add / remove networks
- Multiple networks
- IRCv3 capabilities
    - account-notify
    - away-notify
    - extended-join
    - multi-prefix
    - sasl
    - userhost-in-names
- Initial channel list from LIST
- SSL for IRC connections
