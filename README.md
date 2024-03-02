<!DOCTYPE html>
<html lang="en">
<head>
    <title>Form without sematic HTML</title>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
</head>
<h1>Form without sematic HTML</h1>
<body>
    <form action="">
        <label for="Fullname"> Fullname </label>
        <input type="text" id="Fullname" name="Fullname" required>
        <label for="Email">Email</label>
        <input type="text" id="Email" name="Email" required>
        <label for="Password"> Password</label>
        <input type="text" id="Password" name="Password" required>
        <label for="Gender"></label>
        <select name="Gender" id="Gender">
            <option value="Male">Male</option>
            <option value="Female">Female</option>
            <option value="Other">Other</option>
        </select>
        <label for="Newletter">Subscribe to Newletter </label>
        <input type="checkbox" id="Newletter" name="Newletter" >
        <label for="Comment">Comment</label>
        <textarea name="Comment" id="Comment"  rows="4"></textarea>
       <button type="submit">submit</button>
    </form>
</body>
</html>
