<img src="https://media.discordapp.net/attachments/1279353553110040596/1438757909797273711/content.png?ex=69180b38&is=6916b9b8&hm=d37dcd8fa68bb90a9609d67c8053d6f7ae6f1c504f370ec6b9570fbef172b143&=&format=webp&quality=lossless&width=1313&height=125" width="100%" height="auto" />


# About Me 
<img src="https://media.discordapp.net/attachments/1433593909115617331/1433593909627453613/image_2025-10-10_125759495-Photoroom.png?ex=6917b6de&is=6916655e&hm=81b7d0903ec297b9950f6e9ff5e9eac4a85ddf45773d90b553ca1dc82bc00671&=&format=webp&quality=lossless&width=440&height=771" width="130px" align="left" style="border-radius: 10px; margin-right: 15px;" />

```powershell
function Set-UserProfile {
    $nickname = "Senko"
    $gender = "Male"
    $userID = "<@1124389055598170182>"

    $personality = @{
        Playful = $true
        Enthusiastic = $true
    }

    $interests = @("Anime", "Discord", "Coding")
    $favorite_anime = "Clannad"

    $skills = @("Discord Bot Development", "Python Programming")

    $goal = "Pursuing a BS in Computer Science"
    $status = "Currently in college..."

    $inspiration = "Oliver (Creator of Poketwo)"

    Write-Host "Nickname: $nickname"
    Write-Host "Gender: $gender"
    Write-Host "User: $userID"
    Write-Host "`n# Personality"
    Write-Host "Playful: $($personality.Playful)"
    Write-Host "Enthusiastic: $($personality.Enthusiastic)"
    Write-Host "`n# Interests"
    $interests | ForEach-Object { Write-Host "Interest: $_" }
    Write-Host "Favorite Anime: $favorite_anime"
    Write-Host "`n# Skills"
    $skills | ForEach-Object { Write-Host "Skill: $_" }
    Write-Host "`n# Goals"
    Write-Host "Goal: $goal"
    Write-Host "Status: $status"
    Write-Host "`n# Inspiration"
    Write-Host "Inspiration: $inspiration"
}

Set-UserProfile
```

<br/><br/><br/>


<br/><br/><br/>
