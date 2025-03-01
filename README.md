<div align="center">
  <h1>Jacksonbot </h1>
A general-purpose Discord bot with some cool features. <br />
</div>

### Features & Roadmap
- Fully integrated accounts system and economy, with fun ways to earn and spend currency
  - Auditable transaction and exchange records, detailing where money is going
- Several minigames including modern Blackjack, trivia questions and slot machines
  - Statistics recorded for all games, allowing users to track progress and compare with other users
  - More games and activities coming soon
- DnD-style dice rolling & RNG, allowing users to roll custom dice (i.e. `d20+d48`)
- Profile system with custom colours, descriptions, and earnable badges

  
### Requirements
- A [Discord bot application](https://discordapp.com/developers/applications/) with registered user and token (app -> Bot -> Add Bot)
- .NET 5.0 Runtime (SDK for building) or newer
- PostgreSQL (tested with 13.1)
    - Modify the connection string in `jacksonbot.appsettings.example.json` to your database

You can use the `tools/jacksonbot.service` file to run Jacksonbot as a `systemd` service. 
