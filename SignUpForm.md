<!DOCTYPE html>
<html lang="es">
    <body>
        <h1>Sign Up</h1>
        <label for="email">Email: </label>
        <input type="text" id="email" placeholder="Enter your email" style="margin-bottom: 20px;" maxlength="20" required><br>
        <label for="password">Password:</label>
        <input type="password" id="password" placeholder="Enter your password" maxlength="20" required><br>
        <h3>Date of Birth:</h3>
        <table>
            <tr>
                <td>
                    <label for="day">Day:</label>
                    <input type="number" id="day" placeholder="DD" min="1" max="31" required>
                </td>
                <td>
                    <label for="month">Month:</label>
                    <input type="number" id="month" placeholder="MM" min="1" max="12" required>
                </td>
                <td>
                    <label for="year">Year:</label>
                    <input type="number" id="year" placeholder="YYYY" min="1900" max="2023" required>
                </td>
            </tr>
        </table>
        <h3>Gender:</h3>
        <select style="margin-bottom: 40px;" required>
            <option value="">Select Gender</option>
            <option>Male</option>
            <option>Female</option>
            <option>Rather not say</option>
            <option>Unknown</option>
        </select><br>
        <button id="submit">Sign Up</button>

    </body>
</html>
