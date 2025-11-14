[![Typing SVG](https://readme-typing-svg.herokuapp.com?color=FFF&width=600&pause=1600&center=false&vCenter=false&repeat=true&lines=Introduction(%22senko-sleep%22);Welcome+to+my+README;I+code+projects+and+tools;Feel+free+to+check+out+some+of+my+projects)](https://git.io/typing-svg)

<img src="https://avatars.githubusercontent.com/u/166271770?v=4" width="130px" align="left" style="border-radius: 10px; margin-right: 15px;" />

<br/><br/><br/>

# About Me 
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
