 Telegram Bot Repo Capable of fetching the following Info via Anilist API inspired from AniFluid and Nepgear

    •Anime
    •Airing
    •Manga
    •Character
    •Scheduled
    •Top animes
    •Favourites
    •Anilist Activity
    •Update Anilist entry using
     bot
    •Popular, trending and
     upcoming animes for a
     season
    •Random anime quotes
    •Anime fillers from
     animefillerslist
    •Anime Airing notifications
     from LiveChart
    •Anime Headlines from
     LiveChart
    •Anime release
     notifications for
     Crunchyroll
    •Anime release
     notifications for
     Subsplease
    •Anime Reverse Search
     Powered by tracemoepy
    •Watch Order from Chiaki
     using web api

 Also can add to grps and enable sfw lock to prevent members from looking up hentai and 18+ rated stuff Also includes command disabling

Requirements

    •Python 3.9.6
    •Telegram API Keys
    •Bot Token from BotFather
    •SauceNAO API Keys
    •MongoDB Database URL
    •Anilist Client Keys
    •For smooth authentication
     process deploy this
     webserver (well a noob
     code server hope this
     helps)

Available Cmds
 
    /help - Get interactive and detailed help on bot cmds 
    /ping - Ping the bot to check if it's online 
    /start - To start bot in group (will be logged) or pm (user if not OWNER will be logged) 
    /anime - Fetches info on single anime (includes buttons to look up for prequels and sequels) 
    /anilist - Fetches info on multiple possible animes related to query 
    /character - Fetches info on multiple possible characters related to query 
    /manga - Fetches info on multiple possible mangas related to query
    /airing - Fetches info on airing data for anime
    /flex - Fetches anilist info of an authorised user
    /user - Fetches anilist info as per query
    /schedule - Fetches scheduled animes
    /auth - Fetches info on how to authorize anilist account
    /browse - get popular, trending or upcoming animes 
    /quote - get random quotes
    /logout - removes authorization
    /settings - To toggle nsfw lock and airing notifications in groups
    /top - to retrieve top animes for a genre or tag
    /reverse - Reverse search powered by tracemoepy 
    /watch - Fetches watch order for anime series 
    /feedback - contact bot owner or main support grp at @hanabi_support
    /me or /activity - Get Anilist recent activity
    /fillers - To get list of anime fillers
    /disable - To disable a command in group
    /enable - To enable a command in group
    /disabled - To list disabled commands in a group
    /favourites - Get Anilist favourites
    /gettags - Get list of available Tags
    /getgenres - Get list of available Genres

Owner/Sudo Cmds
 
    /eval - Runs python code (code must start right after cmd like "/eval print('UwU')")
    /term - Runs the code in terminal
    /stats - Gibs data on bot such as no. of grps/users and ping
    /dbcleanup - Cleans useless entries in database

Credits

    •AniList Api (GitHub)
    •jikanpy (GitHub)
    •@NotThatMF for chiaki
     fast api and for creating
     base for this bot to work
    •@DragSama on telegram
     for tracemoepy & AniFluid-
     Base
    •@DeletedUser420 on
     telegram for USERGE-X &
     Userge-Plugins
    •Phyco-Ninja as author of
     anilist plugin in Userge-
     Plugins repo
    •@blank_x on tg for
     sukuinote

For improvements PR or contact @LostB053 or @hanabi_support Can ask for support too but don't expect much (since i myself am learning yet)


Note: I dropped SauceNAO stuff cuz i couldnt represent it in some good looking manner I would be grateful if anybody can help me parse results and organize them like @reverseSearchBot Something nearby but good looking would suffice too
