Go to root directory
Run "npm init -y"
Update package.json with: "start":"node server.js"
Run "npm install express sequelize mysql2 dotenv bcrypt express-handlebars express-session connect-session-sequelize"
After creating the schema.sql, do this:
1. From root directory, type "mysql -u root -p"
2. Create the database: "source db/schema.sql"
3. Confirm it worked: "show databases;"
4. Type "quit" and press Enter


To perform TDD (Test-Driven Development):
1. Type "npm i jest -D"
2. Update package.json: "test": "jest"
3. Type "npm run test" to do the testing