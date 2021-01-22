# zombobox
IPTV quick demo app (iOS and tvOS targets). 
Project is not compiles on perpose. You need to find m3u8 playlist url in the Internet and put that in the code.

So... you need to put m3u8 url with IPTV streams in code, compile, start app on Apple tv (or iOS device), wait a second, choose channel, wait a little bit more, hopefully in the end of this strugling you'll enjoy with some streaming.


https://stackoverflow.com/questions/52175030/swift-how-to-parse-logo-image-from-m3u-playlist
-------------------------------------------------------------
v1rusprox

Config.swift

import Foundation

struct Config {
static let playlistURL = URL(string: "http://online-tv.ipnet.ua/ipnet.m3u8")! ///TODO: past
// m3u8 url with streams.
}
