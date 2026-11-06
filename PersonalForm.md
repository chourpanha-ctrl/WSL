<!DOCTYPE html>
<html>
    <body>
        <form>
            <label for="username">Username: </label>
            <input type="text" id="username" name="username" placeholder="Enter your username"><br>
            <label for="email">Email: </label>
            <input type="text" id="email" name="email" placeholder="Enter your email"><br>
            <label for="userpassword">Password: </label>
            <input type="password" name="userpassword" id="userpassword" placeholder="Enter your password">

            <p>User Type:</p>
            <input type="radio" name="usertype" id="student" value="student">
            <label for="student">Student</label><br>
            <input type="radio" name="usertype" id="teacher" value="teacher">
            <label for="teacher">Teacher</label>

            <p>Interests: </p>
            <input type="checkbox" name="interests" id="sports" value="sports">
            <label for="sports">Sports</label><br>
            <input type="checkbox" name="interests" id="music" value="music">
            <label for="music">Music</label><br>
            <input type="checkbox" name="interests" id="technology" value="technology">
            <label for="technology">Technology</label><br>

            <button type="submit">Sigh Up</button>
            <button type="reset">Clear</button>
        </form>
    </body>
</html>
