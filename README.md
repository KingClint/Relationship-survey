# A Relationship Survey

Hi there, this is my first repository created. OK not first but second. I deleted the first. I didn't know my way around so I was just cruising. lol.
In this repo, the idea is to put out there my very first project in programming; A relationship survey. The beginninig of my programming journey.

The html

<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="UTF-8">
        <title>Relationship Survey</title>
        <link rel="stylesheet" href="relationshipSurveyStyles.css">
    </head>
    
    <body>
        <div class="content">
        <h1>Relationship Survey</h1>
        <p><em>Thank you for taking time to fill this form. I really appreciate it.</em></p>
        <form id="relationship-survey" action="https://register-demo.freecodecamp.org">
            <fieldset>
                <label>
                    Name: <input type="text" name="full-name" placeholder="Enter your full name" required />
                </label>
                <label>
                    Age: <input type="number" name="age" placeholder="Enter your age" min="16" max="200" required /><br>
                </label>
                <label>Gender:<br>
                     <input type="radio" name="gender" />Male <br>
                     <input type="radio" name="gender" />Female <br>
                     <input type="radio" name="gender" />Other <br><textarea rows="0" cols="0" name="gender" placeholder="Please Specify..."></textarea>
                </label>
                <label>
                    Email: 
                    <input type="email" name="email" placeholder="Enter your email" required />
                </label>
                
            </fieldset>
            <fieldset>
                <label>What has been the longest duration of all your relationships?<br>
                <input type="radio" name="relationship-duration" />Below 6 months <br>
                <input type="radio" name="relationship-duration" />6 months to 1 year <br>
                <input type="radio" name="relationship-duration" />1 year to 2 years <br>
                <input type="radio" name="relationship-duration" />Above 3 years <br>
                </label>
                <label>How many relationships have you been in?
                    <select>
                        <option value="0">Select any</option>
                        <option value="1">1 relationship</option>
                        <option value="2">More than 1 relationship</option>
                    </select>
                </label>
            </fieldset>
            <fieldset>
                <label>What is your love language? <br>
                  <input type="checkbox" name="love-language" />Physical Touch <br>
                  <input type="checkbox" name="love-language" />Words of Affirmation <br>
                  <input type="checkbox" name="love-language" />Gifts <br>
                  <input type="checkbox" name="love-language" />Quality Time <br>
                  <input type="checkbox" name="love-language" />Acts of Service <br>
                </label>
                <label>Whats your ideal type of partner? <br>
                    <textarea rows="3" cols="30" name="idea-partner" placeholder="Enter comments here..."></textarea><br>
                </label>
                <label>In your own words,  what is love? <br>
                    <textarea rows="3" cols="30" name="idea-partner" placeholder="Enter comments here..."></textarea><br>
                </label>
            </fieldset>
            <input type="submit" value="Submit">
        </form>
    </div>
    </body>

</html>
