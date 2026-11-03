# wrecht

**media infrastructure · automation · security research**

i build the unglamorous layer that makes media actually work: the server, the
automation feeding it, the clients that have to decode whatever the file throws
at them, and the protocols that were never meant to talk to each other.

if it involves getting video to play somewhere it shouldn't have to, i've
probably lost a weekend to it.

i write scripts and bots to automate things that absolutely did not need
automating, which is the entire point.

## what i'm building

**starhold** — a self-hosted media suite with a jellyfin-compatible api and a
footprint measured in megabytes, not gigabytes. go server, svelte admin, kotlin
multiplatform clients, and a native mpv companion for the codecs browsers refuse
to touch. the main suite is private (access on request); the public pieces:

- [**starhold-companion**](https://github.com/Wrecht-Dev/starhold-companion) — native-messaging host that hands playback to installed mpv. no transcoding, no quality loss.
- [**starhold-native**](https://github.com/Wrecht-Dev/starhold-native) — kotlin multiplatform client for android, android tv, ios, macos, windows, and linux.

**curated-iptv** — a self-healing iptv playlist: daily hls probes, dead-stream
repair, and a github pages publish. [repo](https://github.com/Wrecht-Dev/curated-iptv).

## security research

i break things on purpose, then write down what happened. recent work is in
web/api authorization and evm relay surfaces — a private cantina case study
(confirmed Medium) and a small ai-assisted bounty pipeline for recon, triage, and
reporting. the interesting part is not the automation; it's knowing which
findings are real.

case studies available on request.

## currently

shipping starhold, poking at relay and bridge authorization bugs, and teaching a
bounty pipeline to do the boring 80% without pretending it can do the last 20%.

## stack

| | |
|---|---|
| **languages** | `go` · `typescript` / `svelte` · `kotlin` · `dart` / `flutter` · `python` · `node` · `rust` |
| **infra** | `sqlite` · `ffmpeg` · `linux` · `docker` · `github actions` |

## elsewhere

- x: [@ShredTheLogs](https://x.com/ShredTheLogs)
- cantina: [cantina.xyz/u/wrecht](https://cantina.xyz/u/wrecht)

---

this profile is mostly a workshop. if you're reading it anyway — hi.
