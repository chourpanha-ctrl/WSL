<!DOCTYPE html>
<html>
  <body>
    <h1 id="title">Community Feedback Survey</h1>
    <p id="description">Please take a moment to help us improve our services.</p>
    <form id="survey-form">
      <div>
        <label id="name-label" for="name">Name</label>
        <input 
          id="name" 
          type="text" 
          placeholder="Enter your name" 
          required>
      </div>
      <div>
        <label id="email-label" for="email">Email</label>
        <input 
          id="email" 
          type="email" 
          placeholder="Enter your email" 
          required>
      </div>
      <div>
        <label id="number-label" for="number">Age (optional)</label>
        <input 
          id="number" 
          type="number" 
          min="10" 
          max="100" 
          placeholder="Enter your age">
      </div>
      <div>
        <label for="dropdown">Current Role</label>
        <select id="dropdown" name="role">
          <option disabled selected value="">Select current role</option>
          <option value="student">Student</option>
          <option value="job">Full Time Job</option>
        </select>
      </div>
      <div>
        <p>Would you recommend us to a friend?</p>
        <label>
          <input 
            type="radio" 
            name="recommend" 
            value="definitely" 
            checked
          > Definitely
        </label>
        <label>
          <input 
            type="radio" 
            name="recommend" 
            value="maybe"
          > Maybe
        </label>
      </div>
      <div>
        <p>What would you like to see improved? (Check all that apply)</p>
        <label>
          <input 
            type="checkbox" 
            value="front-end"
          > Front-end Projects
        </label>
        <label>
          <input 
            type="checkbox" 
            value="back-end"
          > Back-end Projects
        </label>
      </div>
      <div>
        <label for="comments">Any comments or suggestions?</label>
        <textarea 
          id="comments" 
          name="comment" 
          placeholder="Enter your comment here..."></textarea>
      </div>
      <button id="submit" type="submit">Submit</button>
    </form>
  </body>
</html>
