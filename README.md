Go to root directory
Run "npm init -y"
Update package.json with: "start":"node server.js"
Run "npm install express sequelize mysql2 dotenv bcrypt express-handlebars"
After creating the schema.sql, do this:
1. From root directory, type "mysql -u root -p"
2. Create the database: "source db/schema.sql"
3. Confirm it worked: "show databases;"
4. Type "quit" and press Enter