<img src="https://static.wixstatic.com/media/799fd4_0512b6edaeea4017a35613b4c0e9fc0b~mv2.jpg/v1/fill/w_1200,h_140,al_c,q_80,usm_0.66_1.00_0.01/networknext_logo_colour_black_RGB_tightc.jpg" alt="Network Next" width="600"/>

<br>

# Frequently Asked Questions

## What is Network Next?

Network Next is a marketplace for premium network transit. 

## How does the marketplace work?

We sell 10 second slices of access to private networks via a two-sided marketplace, in other words, we're basically _Google Adwords for Packets_.

## Why use Network Next?

Network Next improves the quality of network transit from players around the world to servers hosted in datacenters. Players have lower latency, fewer hitches, and less packet loss when they play over Network Next.

## How does Network Next work?

Network Next SDK steers UDP game traffic across the best path from players to game servers via centrally planned routing driven by a marketplace bidding system run once every 10 seconds per-player.

## Does Network Next violate Network Neutrality?

No. Routing via bidding process ensures that we remain _supplier neutral_ and always steer traffic across the route with the best performance at the best price, without favoring any one buyer or supplier over another.

## Can suppliers specify a different price depending on the buyer?

No. Suppliers cannot identify buyers on Network Next and therefore cannot provide one price for one buyer, and a different price for another. Suppliers may only compete on performance and price.

## What sort of improvements can Network Next provide?

It depends on the time of day, ISP and location of each player, and on the data center where game server is located... but overall across all players, we are typically able to provide significant performance improvements for at least 10% of a playerbase (>10ms latency reduction, or 1% packet loss reduction or greater).

## What's the biggest improvement Network Next has provided?

We've seen players with over 1000ms round trip time reduced to less than 50ms and players with almost 100% packet loss reduced to zero. This is not the common case, but these players certainly appreciate it :)

## How much does Network Next cost?

The average price per-gigabyte is 10c right now, but because Network Next typically targets only the bottom 10% that need help at any time, the amortized cost is only 1c per-GB.

## Do players have to pay to use Network Next?

No. Players do not have to pay. Our customer is the game developer, not the player.

## How does billing work?

Because the private networks we work with reserve capacity for each player, Network Next bills on the envelope of traffic, rather than the actual usage.

Each month we sum up the total of 10 second bandwidth slices served by all suppliers for a game (often multiple suppliers are involved in each route), and that is the amount we bill to the game developer.

## How can I get access to the Network Next portal

Please contact us at sales@networknext.com and we'll onboard you for a free trial.

## What games use Network Next?

Network Next is in production with [Rocket League](https://rocketleague.com) for several months now, and we accelerate millions of sessions every day. We're also live with several other games we haven't announced yet.

## What suppliers work with Network Next?

We work with top edge computing and infrastructure suppliers such as:

* [Limelight](https://limelight.com)
* [Stackpath](https://stackpath.com)
* [Packet](https://packet.com)
* [Zenlayer](https://zenlayer.com)
* [Multiplay](https://multiplay.com)
* [I3D](https://i3d.com)
* [Vultr.com](https://vultr.com)
* [GameServers.com](https://gameservers.com)
* [AWS](https://aws.amazon.com)
* [Google](https://cloud.google.com/)
* [Azure](https://azure.microsoft.com)
* [Oracle Cloud](https://cloud.oracle.com/)
* [IBM Cloud](https://ibm.com/cloud)

_And many more we can't talk about yet!_

## Where can I host game servers with Network Next?

We support game servers hosted by:

* [Multiplay](https://multiplay.com)
* [I3D](https://i3d.com)
* [Vultr.com](https://vultr.com)
* [GameServers.com](https://gameservers.com)
* [AWS](https://aws.amazon.com)
* [Google](https://cloud.google.com/)
* [Azure](https://azure.microsoft.com)

If you'd like to evaluate Network Next but you host game servers somewhere else, please let us know at sales@networknext.com

## What platforms do you support?

* PC
* Mac
* Linux
* iOS
* PS4
* Xbox One
* Nintendo Switch

Access to console platform support requires proof that you are a registered developer for that platform. Please contact sales@networknext.com for more information.

## What if my platform isn't listed above

Please contact sales@networknext.com so we can understand your use case. Thanks!

## What languages are supported?

The Network Next SDK is written in low-level C style C++ so it's easy to call from other languages. Get involved and contribute a binding for your preferred language to our open source SDK! https://github.com/networknext/sdk

## What locations are supported by Network Next?

Network Next is deployed worldwide. Please contact sales@networknext.com to discuss a trial so we can ensure that we optimally target the location of your game's userbase.

## Do you have an Unreal Engine 4 Plugin?

Yes. Please contact sales@networknext.com 

## Do you have a Unity plugin?

Not yet, but we're actively working on it. Please contact sales@networknext.com and let us know you're interested.

## Can I use Network Next for player hosted servers?

No. We only support acceleration to servers hosted in datacenters with a known public IP.

## Can I use Network Next for my peer-to-peer game?

No. We only support acceleration of client/server traffic between clients and dedicated servers hosted in datacenters.

## Can I use Network Next to accelerate my TCP game?

Not yet, but in the future we may be able to provide benefit via a TCP shim that reduces the impact of packet loss induced head of line blocking. Please contact sales@networknext.com so we can understand your use case.

## Can I use Network Next to accelerate my WebRTC game?

Not yet. We are actively investigating this as an option. Please contact sales@networknext.com

## Will players be disconnected from my game if Network Next goes down?

No. If our SDK cannot talk to our backend for any reason, players automatically fall back to the public internet and are _free_.

## Are you hiring?

Yes. https://www.networknext.com/careers
