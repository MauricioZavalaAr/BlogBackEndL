/// Goal

/// Create a Back End for a Blog Site
/// Create a Front End for our Blog Site
/// Deploy by  Azure
/// Learn about devops and scrum

Create an API for Blog. This API must handle all CRUD functions
    Create, Read, Update, Delete.

/// In this app the user should be able to login, create an account.
Blog page to view all the published items
Dashboard(The user profile page for them to edit, delete and add blog items)

We will talk about folder structure:

Controller//folder  UserController (This will handle all our user interactions)
    Login//endpoints
    Add a User//endpoints
    Update a User
    Delete a User
BlogController//file
    Add Blog items // endpoint C
    GetAllBlogItems// endpoint R
    GetBlogItemsByCategory
    GetAllBlogItemsByTags
    GetBlogItemsByDate 
    UodateBlogItems// endpoint U
    DeleteBlogItems// endpoint D

Model/// folder
    UserModel
        int ID
        string Username
        string Salt
        string Hash 256 characters

    BlogItemModel
        int ID
        int UserID
        string PublishName
        string Title
        string Image
        string Description
        string Date
        string Category
        bool IsPublished
        bool IsDeleted
///------ Items that will be saved to our data base DB are above

    Login Model
        string Username
        string password
    CreateAccountModel
        int ID = 0
        string Username
        string password
    passwordModel
        strubg Salt
        string Hash

ices//folder
Context//folder

UserService//file
    GetUserByUsername
    Login
    Add User
    Delete User

BlogItemsService // file
    Add Blog items // functions C
    GetAllBlogItems// functions R
    GetBlogItemsByCategory
    GetAllBlogItemsByTags
    GetBlogItemsByDate 
    UodateBlogItems// functions U
    DeleteBlogItems// functions D
    GetUserById//functions

    PasswordService//file
        Hash password
        Very Hash Password

///
///
///
///
///
///
///
///
///
//