# myspace-profile
recreation of a myspace profile page

<!DOCTYPE html>
<head>
    <title>Lexy's Myspace Profile</title>
    <link rel="icon" href="hearts.png" type="image/icon type">
    </head>
<body>
    <div class="profile-snapshot">
        <h2 id="header">Lexy Ramos</h2>
        <h4 id="header">Computer Science Student</h4>
        <img id=profile-picture src="Profile picture.JPG" alt="profile picture">
        <p id="about-me">Age: 29<br>Female<br>Independence, Oregon<br>United States<br><br><br>Last Login: 11/5/2023
        </p>
        <p id="mood">Mood: Happy 😀</p>
    </div>
    <div class="music-player">
        <audio controls autoplay src="Dreams (2004 Remaster).mp3" type="audio/mp3">
        </audio>
    </div>
    <div class="interests">
        <table>
            <thead><tr>
                <th colspan="2">Lexy's Interests</th>
              </tr></thead>
            <tr><td>General</td>
            <td>Mom-ing, witch-ing, <br>and sleeping</td></tr>
            <tr><td>Languages</td>
            <td>Python: Advanced, <br>HTML5: Intermediate,<br>CSS: Intermediate, <br>SQL: Beginner,<br> C++: Beginner</td></tr>
            <tr><td>CS Interests</td>
            <td>Front-End Development, <br>UX/UI, Cybersecurity</td></tr>
        </table>
    </div></body>

.profile-snapshot{
    height: 290px;
    width: 300px;
    border: 1px solid hotpink;
    border-radius: 10px;
    background-color: pink;
}
#header{
    margin: 2px;
    padding-bottom: 4px;
    padding-left: 10px;
    color: rgb(255, 0, 144); 
}
#profile-picture{
    float: left;
    padding-right: 20px;
    padding-left: 10px;
    width: 145px;
    height: 200px
}

#about-me{
    color: rgb(255, 0, 144); 
}

#mood{
    position: relative;
    top: 10px;
    right: 150px;
    color: rgb(255, 0, 144); 
}

table, thead {
    border: 1px solid hotpink;
    border-radius: 10px;
    background-color: pink;
    color:  rgb(255, 0, 144);
    width: 300px;
  }
  
  th, td{
    border: 1px solid hotpink;
    border-radius: 5px;
  }