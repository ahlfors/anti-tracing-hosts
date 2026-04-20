# anti-tracing-hosts

# how to use:
1. download hosts to your local hosts.
  if macos, hosts in below location:
  ```
  /etc/hosts
  ```
  if windows, hosts in below location:
  ```
  C:\Windows\System32\drivers\etc\hosts
  ```
3. if macos, then do:
  ```
  sudo dscacheutil -flushcache; sudo killall -HUP mDNSResponder
  ```
  if windows, then do:
  ```
  ipconfig /flushdns
  ```

Or, you can use below well known projects:

🔒 Consolidating and extending hosts files from several well-curated sources. Optionally pick extensions for porn, social media, and other categories.
https://github.com/StevenBlack/hosts

AdAway is a free and open source ad blocker for Android.
https://github.com/AdAway/AdAway

Network-wide ads & trackers blocking DNS server
https://github.com/AdguardTeam/AdGuardHome

NextDNS CLI client (DoH Proxy)
https://github.com/nextdns/nextdns






