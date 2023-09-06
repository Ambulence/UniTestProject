# Test project set up
  ## Description:
  This is a test setup project using the Astro framework technology for the front end and Strapi for the back end and DB.

  ## Installation
  1. To install the project and continue working on it, first, clone the repository locally to your computer. 
  After you've cloned the project to your computer, open it in your IDE.
  ____
  **Warning!!!** The project was developed using VSCode, so it is preferable to use it. Otherwise, you will need to eliminate the errors that you will encounter at the project installation stage yourself. Use the Astro [Astro](https://astro.build/) and Strapi [Strapi](https://strapi.io/) documentation to solve problems.
  ____
  ```python

  # Input in CLI to install dependencies of front-end and back-end
  npm run install

  # Input in CLI to install dependencies of the project
  npm install

  # Input in CLI to run a project 
  npm start

  ```
  2. After the servers are started, you need to go to the address http://localhost:1337/admin/auth/register-admin and register in Strapi.

  3. Then go to **Content Manager->Collection Types->Dog** and **Click** Create new entry 

  4. **Fill required fields: name, breed, photo.**
  
  5. **Click Save and Publish.** Create several entries with different data.

  6. **Set Role and Permission:** Click on the General Settings icon Settings at the bottom of the main navigation

      Under Users & Permissions Plugin, choose Roles.
    
      Click the Public role.
     
      Scroll down under Permissions.

      In the Permissions tab, find Restaurant and click on it.
     
      Click the checkboxes next to find and findOne.

      Finally, click **Save**.

      **Use this hint if you need** [Step 3. Set Roles & Permissions](https://docs.strapi.io/dev-docs/quick-start#_1-install-strapi-and-create-a-new-project)

### After these manipulations, restart your project again with the command 

```bash
npm start
```
After starting the servers, you will be able to open your front end at the address http://localhost:4321/

Here you can see how your UI will look after all operations 
![Project]([http://url/to/img.png](https://share.getcloudapp.com/p9uYgbZj))


# If you want to create your collection!!!
  
  1. **Run servers**
     
      ```bash
      npm run develop
      ```
      
  2. **Follow the addres** http://localhost:1337/admin:

     Go to Plugins **Content-type Builder** in the main navigation.

     Click on **Create new collection type**

     Type **your-category-name** for the Display name, and click Continue.

     Click the Text field.

     Type Name in the Name field.

     Switch to the Advanced Settings tab, and check the Required field and the Unique field settings (if you need them).

     Finally, click Save and wait for Strapi to restart.
     
  
  
