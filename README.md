# Package Tracker - Voice Ability for OpenHome

A voice-driven package tracker that lets users track shipments in real time using the TrackingMore API.

## Setup
1. Get a free API key from [TrackingMore](https://www.trackingmore.com).
2. Place your key in `config.json` (replace the placeholder).
3. Upload the ZIP via OpenHome Dashboard -> Abilities -> Add Custom Ability -> Empty Template.
4. Trigger words: `track my package`, `where's my package`, `package status`, `tracking`

## Usage Examples
- **Add a package** - "Track my package 92612903029511573030094547"
- **List packages** - "List my packages"
- **Check status** - "Where's my package?"
- **Remove a package** - "Remove package 92612903029511573030094547" (confirmation required)

## Notes
- Real-time data requires a valid API key. Without it, the ability will fall back to simulated responses.
- All OpenHome security policies are followed.
