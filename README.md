# SC.NET
[SwimCloud](https://swimcloud.com/) Info Extractor Based On Web Scraping

# Intro

# Docs

Learn About The Full Library, How It Works & Some Examples To Help You Implement

## Team

#### getName()

## Swimmer (int id -> Within Desired Swimmers URL)

#### getName() -> System.String
Returns currently set name for swimmer (First + Last).

#### getLocation() -> System.String
Returns location (City, State).

#### getTeam() -> scnet.Team
Constructs new scnet.Team object by Team ID referenced in scraped HTML element.

#### getTeamName() -> System.String
Alternative to getTeam() if you only want the name & not additional team info.

#### getAllTeams() -> List<scnet.Team>
Constructs a list of all teams this swimmer has ever been on

#### getAllTeamNames() -> List<System.String>
Alternative to getAllTeams() if you only want the names & not additional team info.

#### getMostRecentMeet() -> scnet.Meet
Constructs new scnet.Meet object by Team ID referenced in HTML element of most recently completed / attended meet on profile.

#### getAllMeets() -> List<scnet.Meet>
Constructs a list of all meets this swimmer has ever attended / completed

#### getAllMeetNames() -> List<System.String>
Alternative to getAllMeets() if you only want the meet names & not additional meet info.
